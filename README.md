# Detect and Distort Faces

###### project environment settings

- ref: [PyTorch Mobile Runtime for Android](#tutorial-1)

**Android Studio를 통해 작업 필요.**

- Android 스튜디오를 Linux에 설치 → [developer.android.com](https://developer.android.com/studio/install?hl=ko#linux)

  1) [최신 버전의 Android Studio 다운로드](https://developer.android.com/studio?hl=ko)

  2) 64비트 버전의 Ubuntu를 실행하는 경우, 다음 명령으로 일부 32비트 라이브러리를 설치

     ```shell
     sudo apt-get install libc6:i386 libncurses5:i386 libstdc++6:i386 lib32z1 libbz2-1.0:i386
     ```

  3) 다운로드한 압축파일(예시: `.tar.gz`)을 애플리케이션의 적절한 위치에 압축해제

     ```shell
     tar -zxf /home/hommy_ubuntu/Downloads/android-studio-2021.2.1.14-linux.tar.gz --directory /usr/local/
     cd /usr/local
     ```

  4) Android 스튜디오를 시작

     ```shell
     cd android-studio/bin/
     bash studio.sh
     ```

  5) Android 스튜디오 설정 마법사를 이용하여 설치



###### references

- PyTorch Mobile
  - Github: **Android Demo Examples** [pytorch/android-demo-app](https://github.com/pytorch/android-demo-app)
  - Tutorials: [pytorch.org/mobile](https://pytorch.org/mobile/home/)
    1. <a id="tutorial-1"></a>[PyTorch Mobile Runtime for Android](https://www.youtube.com/watch?v=5Lxuu16_28o)