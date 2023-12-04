# FooBao_Crawling

MacOS 환경에서 chromedriver를 실행하기 위해서는 chromdriver가 있는 디렉토리에서 다음 명령어를 먼저 입력해야 합니다.

chmod +x chromedriver
xattr -d com.apple.quarantine chromedriver

이후 Crawling.ipynb를 실행하면 메뉴사진과 리뷰사진이 크롤링됩니다.

requirements.txt에 있는 라이브러리 버전과 일치시켜야 작동합니다. 특히 Selenium 4의 문법 기준으로 코드가 작성되었습니다.
