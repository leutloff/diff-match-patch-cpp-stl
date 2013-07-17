message("***   Entering the main CMakeLists.txt file  ***")

project (diff-match-patch-cpp-stl CXX)

add_executable(diff_match_patch_test_wstring diff_match_patch_test_wstring.cpp)

add_executable(diff_match_patch_test_string diff_match_patch_test_string.cpp)

