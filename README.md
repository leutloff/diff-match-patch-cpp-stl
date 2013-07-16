diff-match-patch-cpp-stl
========================

C++ STL variant of https://code.google.com/p/google-diff-match-patch.

STL Port was done by Sergey Nozhenko (snhere@gmail.com) and posted on
https://code.google.com/p/google-diff-match-patch/issues/detail?id=25

The STL Port is header only.

Compile and run the test cases:
    g++ diff_match_patch_test.cpp -o diff_match_patch_test && ./diff_match_patch_test

Compile and run the speedtest - requires the files speedtest1.txt and speedtest2.txt for comparison: 
    g++ speedtest.cpp -o speedtest && ./speedtest