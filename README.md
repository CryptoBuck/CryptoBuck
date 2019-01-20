#uncomment the following section to enable building on windows:

windows:LIBS += -lshlwapi
LIBS += $$join(BOOST_LIB_PATH,,-L,) $$join(BDB_LIB_PATH,,-L,) $$join(OPENSSL_LIB_PATH,,-L,) $$join(QRENCODE_LIB_PATH,,-L,)
LIBS += -lssl -lcrypto -ldb_cxx$$BDB_LIB_SUFFIX
windows:LIBS += -lws2_32 -lole32 -loleaut32 -luuid -lgdi32
LIBS += -lboost_system-mgw46-mt-sd-1_53 -lboost_filesystem-mgw46-mt-sd-1_53 -lboost_program_options-mgw46-mt-sd-1_53 -lboost_thread-mgw46-mt-sd-1_53
BOOST_LIB_SUFFIX=-mgw46-mt-sd-1_53
BOOST_INCLUDE_PATH=C:/deps/boost
BOOST_LIB_PATH=C:/deps/boost/stage/lib
BDB_INCLUDE_PATH=c:/deps/db/build_unix
BDB_LIB_PATH=c:/deps/db/build_unix
OPENSSL_INCLUDE_PATH=c:/deps/ssl/include
OPENSSL_LIB_PATH=c:/deps/ssl
CryptoBuck - Valued more than a coin!

Scrypt PoW/PoS

3 Minute block target, linear (per-block) difficulty readjustment

Block Rewards:

1-300 = 1 BUK to allow network to ramp up.

<35000 = 33 BUKs (~60 days)

<70000 = 22 BUKs (~60 to ~120 days)

>70000 = 11 BUKs (~120 days and beyond)

10,000,000 total coinage via Proof of Work

30 Confirms for Coin Maturity

140 Character TX Messaging

3% Proof of stake reward, 30 days to stake, 60 days to full weight

Default RPC Port = 13888

Default P2P Port = 12888

