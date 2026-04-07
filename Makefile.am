if GCOV_ENABLED
SUBDIRS = gcovpreload fpmsyncd neighsyncd portsyncd mclagsyncd natsyncd fdbsyncd orchagent swssconfig cfgmgr gearsyncd
else
SUBDIRS = fpmsyncd neighsyncd portsyncd mclagsyncd natsyncd fdbsyncd orchagent swssconfig cfgmgr gearsyncd
endif

if BUILD_SKIP_TEST_ENABLED
else
SUBDIRS += tests
endif


if HAVE_LIBTEAM
SUBDIRS += teamsyncd tlm_teamd
endif
