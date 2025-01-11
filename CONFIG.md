sudo socat pty,link=/tmp/loopback,raw,user=runner system:cat &
export TEST_PORT=/tmp/loopback
export TEST_BAUDRATE=115200
see tsconfig.json
npm install; npm run format, typecheck, test, build