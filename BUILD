package(default_visibility = ["//visibility:public"])

cc_library(
    name = "leveldb",
    srcs = glob(
        include = [
            "db/**/*.h",
            "db/**/*.c",
            "db/**/*.cc",
            "port/**/*.h",
            "port/**/*.in",
            "table/**/*.h",
            "table/**/*.cc",
            "util/**/*.h",
            "util/**/*.cc",
            "include/**/*.h",
        ],
        exclude = [
            "db/autocompact_test.cc",
            "db/c_test.c",
            "db/corruption_test.cc",
            "db/db_test.cc",
            "db/dbformat_test.cc",
            "db/fault_injection_test.cc",
            "db/filename_test.cc",
            "db/leveldbutil.cc",
            "db/log_test.cc",
            "db/recovery_test.cc",
            "db/skiplist_test.cc",
            "db/version_edit_test.cc",
            "db/version_set_test.cc",
            "db/write_batch_test.cc",
            "issues/issue178_test.cc",
            "issues/issue200_test.cc",
            "issues/issue320_test.cc",
            "port/**/*.in",
            "table/filter_block_test.cc",
            "table/table_test.cc",
            "util/arena_test.cc",
            "util/bloom_test.cc",
            "util/cache_test.cc",
            "util/coding_test.cc",
            "util/crc32c_test.cc",
            "util/env_posix_test.cc",
            "util/env_test.cc",
            "util/env_windows_test.cc",
            "util/env_windows.cc",
            "util/hash_test.cc",
            "util/logging_test.cc",
            "util/no_destructor_test.cc",
            "util/status_test.cc",
            "util/testutil.cc",
        ],
    ),
    defines = [
        "LEVELDB_IS_BIG_ENDIAN=0",
        "LEVELDB_PLATFORM_POSIX=1",
        "HAVE_FULLSYNC=1",
    ],
    includes = [
        "include",
    ],
)
