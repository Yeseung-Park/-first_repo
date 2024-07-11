## Git의 영역

1. **Working Directory**
    - 실제 작업중인 파일들이 위치하는 영역
    - git으로 관리되는 영역
2. **Staging Area**
    - Working Directory에서 변경된 파일 중, 다음 버전에 포함시킬 파일들을 선택적으로 추가하거나 제외할 수 있는 중간 준비 영역
    - 실질적으로 버전 관리를 할 파일을 선별하는 공간
3. **Repository**
    - 버전 이력과 파일들이 영구적으로 저장되는 영역
    - 모든 버전과 변경 이력이 기록됨
    - 변경 사항이 버전 이력으로 저장되는 영역

---

### Commit = 버전 = snapshot
변경된 파일들을 저장하는 행위

---

**git init**: 해당 폴더를 git으로 관리를 할 준비
```
git init
```

**git add**: 변경 사항이 있는 파일을 staging area에 추가

**git commit**
    - staging area에 있는 파일들을 저장소에 기록
    - 해당 시점의 버전을 생성하고 변경 이력을 남기는 것

**Working directory -> git add -> staging area -> git commit -> repository**