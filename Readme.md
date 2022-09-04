## NodeJS

### npm init
* 패키지 의존성을 관리할 package.json 파일을 만드는 명령어

### npm install (plugin)
* npm으로 해당 프로젝트에 패키지(plugin)를 설치

### npm install (plugin) --save
* 패키지(plugin)를 ./node_modules 디렉터리에 설치하고 ./package.json 파일의 dependencies 항목에 패키지 정보가 저장됩니다.
* --production 빌드 시 해당 패키지가 포함됩니다.

### npm install (plugin) --save-dev
* 패키지(plugin)을 ./node_modules 디렉터리에 설치하고 ./package.json 파일의 devDependencies 항목에 패키지 정보가 저장됩니다.
* --production 빌드 시 해당 패키지는 포함되지 않습니다.