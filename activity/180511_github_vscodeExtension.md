## git & github

1. 오류 대처

   1. 오타 확인
   2. 오류메시지를 복사해서 구글링 (보통 stack of flow에 해답이 많음)

2. GitHub 사용 시 유의사항

   * 업로드한 코드를 github 계정에서 되도록 수정하지 않기

3. Fork

   1. fds10-cowoking repo Fork 하기

      repo url: https://github.com/austinpark420/fds10-cowoking

   2. Local PC로 다운받기

      ```
      # path: Documents/dev/

      $ git clone https://github.com/username/fds10-cowoking
      ```

   3. Remote 등록

      ```
      # path: Documents/dev/fds10-cowoking

      $ git remote add upstream https://github.com/austinpark420/fds10-cowoking
      ```

   4. git remote command으로 upstream 등록확인

      ```
      # path: Documents/dev/fds10-cowoking

      $ git remote
      ```

      ​

4. fds10-cowoking 최신 version을 Local PC로 업데이트 하기

   (pull을 받으신 다음에 repo작성하기!!)

   ```
   $ git pull upstream master
   ```



### 참조

* https://help.github.com/articles/merging-an-upstream-repository-into-your-fork/
* https://git-scm.com/docs/git-remote




## VScode extentsion

* Auto Close Tag
* Bracket Pair Colorizer
* Material Icon Theme (선택)

