Git branch

## branch 관련 명령어

> Git 브랜치를 위해 **root-commit을 발생**시키고 진행하세요.

```bash
$ git init ㄷ
$ touch README.md
$ git add .
$ git commit -m 'README!'
$ git log # 확인
```

1. 브랜치 생성

    ```bash
    (master) $ git branch 브랜치명
    ```

2. 브랜치 이동

    ```bash
    (master) $ git checkout 브랜치명
    ```

3. 브랜치 생성 및 이동

    ```bash
    (master) $ git checkout -b 브랜치명
    ```

4. 브랜치 삭제

    ```bash
    (master) $ git branch -d 브랜치명
    ```

5. 브랜치 목록

    ```bash
    (master) $ git branch
    ```

6. 브랜치 병합

    ```bash
    (master) $ git merge 브랜치명
    ```

	* master 브랜치에서 브랜치명을 병합