Prerequesites:
sampctl : https://github.com/Southclaws/sampctl/releases
    - Wiki : https://github.com/Southclaws/sampctl/wiki
Cmake : 3.10+
G++ : std--17++

sampctl ensure
sampctl build --verbose
sampctl run : 
    sampctl run PoC (Proof of concept, runs main only) port 8080
    sampctl run test (runs tests in format of y_testing) port 8080
    sampctl run prod (runs the server as is from pawn.json) port 7777