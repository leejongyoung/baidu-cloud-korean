# 바이두 클라우드 클라이언트 한글화

이 패치는 바이두 클라우드 동기화 프로그램에서만 사용이 가능합니다.
네트워크 디스크 방식은 패치를 지원하지 않습니다.

- 2021-01-28: 티스토리 블로그 폐쇄로 인한 Github로 이전
- 2017-04-21: 파일 유실로 인한 배포 중단
- 2015-12-06: 싱크 프로그램 한글화 티스토리 최초 배포

## 바이두 클라우드 설치하기 

### 공식 홈페이지에서 다운로드
- [다운로드](https://issuecdn.baidupcs.com/issue/netdisk/mac_tongbupan/tongbupan_2.4.6.dmg)

### Brew Cask 설치
``` sh
# 동기화 방식 다운로드
brew install --cask baiducloud
```

## 패치 적용

패치 파일을 다운로드 후 
`/Applications/百度云同步盘.app/Contents/Resources` 경로에 붙여넣기 합니다.

### 터미널로 옮기기

``` sh
git clone https://github.com/leejongyoung/baidu-cloud-korean.git
cd baidu-cloud-korean
mv * /Applications/百度云同步盘.app/Contents/Resources
```