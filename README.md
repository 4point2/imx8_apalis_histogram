# imx8_apalis_histogram

###TO RUN:
Login to your apalis bard and run:

`docker run --user torizon -e ACCEPT_FSL_EULA=1 --rm --name=open_cv  --net=host --cap-add CAP_SYS_TTY_CONFIG -v /dev:/dev -v /tmp:/tmp -v /run/udev/:/run/udev/ --device=/dev/video0 --privileged pgoslawski/open_cv
Opening camera idx 0`

use extra `-p` for detached mode