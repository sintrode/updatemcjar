# updatemcjar
A shell script for updating the Minecraft server jar file on Windows.

# USAGE
    -f, --force      If the Target Version SHA1 matches the current
                     file's SHA1, force the update anyway, implies --yes
    -h, --help       Print this help message
    --jar-path       Specify a different final JAR path, default is
                     %JAR_PATH%
    --manifest       Specify a different version manifest URL, default
                     is %VERSION_MANIFEST%
    --no-err         Suppress error messages (Dangerous!)
    -s, --silent     Suppress script output, implies --yes
    -t, --test       Test the Target Version SHA1 against the current
                     file's SHA1 without changing any files
    --temp-dir       Specify a different temporary directory,
                     default is %TEMP_DIR%
    -v, --version    Specify a different target version; without this
                     parameter, the latest release version is used
    -y, --yes        Skip update confirmationecho
