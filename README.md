# imageTeller
이미지를 올리면 무엇인지 확인해줌.

# 참조
https://blog.keras.io/building-a-simple-keras-deep-learning-rest-api.html


# 실행 방법

' cf push


python buildpack 사용

# 필요 파일 한번에 다운로드 (optional)

mkdir -p vendor
python -m pip download  -r ..\requirements.txt --platform manylinux1_x86_64 --only-binary=:all:
