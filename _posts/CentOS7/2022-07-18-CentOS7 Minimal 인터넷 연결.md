---
title: "CentOS7 Minimal 인터넷 연결"
excerpt: "CentOS7 Minimal 인터넷 연결하기"

categories:
  - CentOS7
tags:
  - [CentOS7, Github]

toc: true
toc_sticky: true

date: 2022-07-18
last_modified_at: 2022-07-18

author_profile: true

---

## CentOS7 Internet Setting

### 1) 인터넷 설정하기
<pre class="black"><code>
  # nmcli d
  # nmtui
</code></pre>
  
nmcli d 로 무선 인터넷 이름을 확인한다. 아는 필요 없음.

nmtui   명령어로 해당 무선 인터넷 정보를 입력

<b>※ 무선 인터넷 비밀번호 입력 시 꼭!!!!! 키보드의 설정 확인이 필요하다!!</br>
이 부분 확인안하고 진행했다가 인터넷 연결이 안되어서 고생함!!</b>
