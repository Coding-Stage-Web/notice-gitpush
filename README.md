# Github으로 과제 제출하기

## 1. Codingstage Github Organization 방문하기 
<img width="500" alt="오가니제이션" src="https://user-images.githubusercontent.com/93020734/224780850-ea99d0be-cab2-4a8b-8dc8-7f9f78c306ac.png">

## 2. 내 Repository 찾기(검색창에 Repository 이름 치면 나와요⚡)
<img width="467" alt="화면 캡처 2023-03-14 023027" src="https://user-images.githubusercontent.com/93020734/224781527-85540a23-2eb5-49da-a905-d691ecdda616.png">

## 3. 클론할 URL 복사하기
<img width="500" alt="화면 캡처 2023-03-14 023242" src="https://user-images.githubusercontent.com/93020734/224781826-8204347f-838e-4167-9aaa-ff940f11c3d2.png">

## 4. 명령 프롬프트 열기

## 5. 내가 프로젝트를 관리할 디렉토리(내 프로젝트가 포함된 폴더)로 이동한다. cd~

## 6. Repository Clone하기 

    git clone {아까 복사한 url}

여기서 중괄호는 넣지 말아주세요!!

    🔥 어쩌구저쩌구 done 이라 나오면, clone이 완료된 거랍니다. 
    그럼 여러분의 repository의 이름으로 폴더가 생성될 거에요.

    이동해봅시다.

    cd {여러분의 디렉토리 이름}
    
## 7. 브랜치 생성하기 

브랜치는 작업환경을 분리해주는 친구임돵

우리는 매주 과제마다 브랜치(week1 - week2 - week3 - ...)를 생성할거에요!

1주차 과제를 진행한다고 가정하고 week1 이라는 브랜치를 만들어봐요.

우선 git이 활성화 되어있는 여러분 레포이름으로 되어있는 디렉토리로 이동해봅시다.

다음 명령어를 통해서 week1 브랜치를 생성해보아요.

    git branch week1
    
잘 생성되었는지 확인해보기 

    git branch
    
<img src="https://user-images.githubusercontent.com/93020734/224785275-317444c9-3c7b-4ce0-a546-6ade11d7c04e.png" width="120" />

위와 같이 week1 브랜치가 나온다면 잘 생성되었네요!

## 8. 생성한 브랜치로 이동하기 

브랜치를 만들었으면 해당 브랜치로 이동해야겠죠?

다음 명령어를 사용해서 이동해봅시다.

    git checkout week1
    
** 생성과 이동을 한 번에 하는 명령어 

    git checkout -b week1
    
    
## 9. 생성한 브랜치에서 작업하고 커밋하기 

    git status
    
<img src="https://user-images.githubusercontent.com/93020734/224786598-71cc844d-9aed-4665-80c4-3264035c30d4.png" width = "250" />

여러분의 파일을 작업한 뒤에, git bash에 이 명령어를 작성해주세요.

    git add .
    
    🔥  "." 이 의미하는 것은 전체에요. 
    추적 중이지 않은 "모든 파일"을 추적하겠다는 뜻입니다.
    
🙋🏻‍♂️ "여기서 커밋이란?"

    음 ... 작업한 것에 대한 변경점을 기록한다! 는 의미에요.

    작업환경의 현재상태를 사진을 찍어놓는 듯한 ... 스냅샷과 같은 역할을 한답니다.

    특정 커밋의 상태로 환경을 돌릴 수도 있고.
    커밋 단위로 어떤 작업을 했는지 확인할 수도 있어요.

    Git을 사용하는데 있어 가장 중요한 역할을 해요.

    그렇기 때문에
    "커밋의 단위"를 잘 나누는 것이 중요해요!

    모든 과제를 완료할 때까지 한 번도 커밋을 하지 않다가 모두 완성하고 커밋을 한다면?

    작업환경의 기록은 딱 두가지로 나뉘겠죠.
    과제를 완성하기 전과 후! 

    **커밋 단위를 잘 나누는 습관을 들여봅시다 우리!
    
그럼 한 번 커밋을 작성해봅시다.


    
    




    
