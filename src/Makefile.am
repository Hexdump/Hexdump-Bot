bin_PROGRAMS = hexdump_bot
hexdump_bot_CFLAGS = $(PYTHON_CFLAGS) $(CFLAGS)
hexdump_bot_LDADD = $(PYTHON_LDFLAGS) $(PTH_LDFLAGS) -lpthread
hexdump_bot_SOURCES = main.c network.c sendqueue.c inqueue.c python_api.c irc_bindings.c irc_struct.c irc.c util.c
