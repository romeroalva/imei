# Code Citations

## License: ISC
https://github.com/SoftCreatR/imei/tree/c3fecccfd528916631bb0d67400fb6d71522ec08/imei.sh

```bash
#############
# Variables #
#############

if [ -z "$WORK_DIR" ]; then
  WORK_DIR=/usr/local/src/imei
elif [ -d "$WORK_DIR" ] && [ "$(ls -A $WORK_DIR)" ]; then
  echo -e "${CRED}Work Dir $WORK_DIR is not empty!${CEND}" >&2
  return 1
fi

if [ -z "$BUILD_DIR" ]; then
  BUILD_DIR=/usr/local
fi

if [ -z "$CONFIG_DIR" ]; then
  CONFIG_DIR="$BUILD_DIR/etc"
fi
```

