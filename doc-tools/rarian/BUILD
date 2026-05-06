sed -i '/srunner_add_suite(sr, rarian_man_suite());/d' tests/check-main.c &&
export LANG=C LC_ALL=C
autoreconf -fvi &&

OPTS+=" --disable-static"

default_build
