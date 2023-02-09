---
layout: post
title: web github
date: 2023-02-09 23:18 +0800
last_modified_at: 2023-02-09 01:08:25 +0800
tags: [web, jekyll, tutorial]
toc:  true
---

### github web

github로 블로그를 만들어 볼까하다가 이미 네이버 블로그/티스토리가 존재하기에 PR용 페이지를 만들면서 작성한 글입니다.

github을 써본 적이 있으시다면 굉장히 쉬운 내용이고 그렇지 않더라도 아래처럼 따라하면 손쉽게 만들 수 있습니다. (깃허브에 가입했다는 전제하에 작성되었습니다.)

Github에 개인 사이트 만들기
깃허브에 접속하여 로그인합니다.

좌측상단에 Repositories 옆에있는 [New]버튼을 클릭하여 새로운 레파지토리를 생성합니다.



github.com

Repository name은 주로 "Owner_ID.github.io"로 합니다.
(저는 moonsiri 여서 moonsiri.github.io로 입력했습니다.)



create a new repository

Initialize this repository with a README 를 선택(check)한 뒤, [Create repository] 버튼을 클릭합니다.
Repository 생성이 완료되었으니, 웹 사이트 마크업을 받아봅시다.

http://jekyllthemes.org/에 접속하여 원하는 테마를 다운받습니다.
(저는 http://jekyllthemes.org/themes/Minimal-Resume/에서 다운받았습니다.)



jekyllthemes.org

테마를 다운받았다면, 생성된 레파지토리 화면에서 [Upload Files] 버튼을 클릭합니다.


github.com/moonsiri/moonsiri.github.io

다운받은 테마 zip 압축을 풀고 Drag 하여 모든 파일을 옮겨넣은 후, 하단의 [Commit changes] 버튼을 클릭합니다.


uplaod files

파일이 업로드되면 _config.yml 파일 등 정보를 수정하면됩니다. (바로 적용되지 않습는다.)


github.com/moonsiri/moonsiri.github.io

Repository Name을 URL 입력창에 입력하면 설정 끝!
(https://moonsiri.github.io/)