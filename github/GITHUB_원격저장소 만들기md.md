# 🕵️‍♀️ GITHUB

![image-20220710043903859](C:\Users\LGE\Desktop\TIL\github\GITHUB_기본으로 알고 있어야한다.assets\image-20220710043903859.png)

#### 📂Section 1.  GITHTB도 버전(COMMIT)을 관리한다. 

> 앞서 배웠던 Git에 대해 알아보고자 할때 GitHub에대해서도 잠깐 알아본적이 있었다. 
>
> 다시말해, GitHub은 프로젝트 디렉토리에서 작업하던 내용을 그대로 외부의 컴퓨터에 전송한다는 뜻이다.  여기서 작업하던 내용을 전송한다는 건, **레포지토리를 전송**한다는 뜻
>
> 그대로 전송하게 되면, 버전관리와 작업이 가능하다. 



![image-20220710043958652](C:\Users\LGE\Desktop\TIL\github\GITHUB_기본으로 알고 있어야한다.assets\image-20220710043958652.png)

https://github.com/



---

#### 📂 Section 2. GITHUB 에서 원격 저장소 만드는 방법 

![image-20220710045807909](C:\Users\LGE\Desktop\TIL\github\GITHUB_기본으로 알고 있어야한다.assets\image-20220710045807909.png)

> 1. new repository 를 생성해 줍니다. 

![image-20220710045917772](C:\Users\LGE\Desktop\TIL\github\GITHUB_기본으로 알고 있어야한다.assets\image-20220710045917772.png)

> 2. Repository 의 이름 설정과 Repository Description 저장소의 설명을 간략히 작성해 줍니다. 

![image-20220710050033063](C:\Users\LGE\Desktop\TIL\github\GITHUB_기본으로 알고 있어야한다.assets\image-20220710050033063.png)

> 3. public으로 설정 후 ![image-20220710050054954](C:\Users\LGE\Desktop\TIL\github\GITHUB_기본으로 알고 있어야한다.assets\image-20220710050054954.png) 을 해줍니다. 

![image-20220710050155834](C:\Users\LGE\Desktop\TIL\github\GITHUB_기본으로 알고 있어야한다.assets\image-20220710050155834.png)

> 4. `https://github.com/oiosu/HTML-CSS.git `
>
>    oiosu : username / HTML-CSS : Repository name 

![image-20220710050355702](C:\Users\LGE\Desktop\TIL\github\GITHUB_기본으로 알고 있어야한다.assets\image-20220710050355702.png)

> 5. `git remote add origin https://github.com/oiosu/HTML-CSS.git`
>
> 원격 저장소 정보를 로컬 저장소에 추가해 준빈다. 이때 로컬 저장소에는 한번만 설정하면 됩니다. 

* ⭐ **`git remote add origin https://github.com/oiosu/HTML-CSS.git`**
  * remote : 원격저장소 
  * add : 추가해줘 
  * origin(원격 저장소의 이름) : origin으로 
  * oiosu : username
  * HTML-CSS : Repository name 

---



#### ✅ [origin, main, HEAD 의 의미](https://www.inflearn.com/questions/27696)

* **origin** 

  * 원격 저장소의 경로 이름 
  * 원격 저장소 추가 명령어 : git remote add [이름] [url]
  * git remote add origin url 형식으로 원격 저장소를 추가하거나 git clone을 통해 원격 저장소를 복사한다면 자동으로 origin이라는 이름의 원격 저장소가 등록되게 됩니다. 

* **main**

  * 브랜치 중 가장 중심의 되는 기본적인 branch 를 master 또는 main이라고 합니다. 

* **HEAD** 

  * 내가 어떤 작업 공간에 있는지 알려줍니다. 
  * 만약 브랜치를 main, dd 라는 브랜치를 생성하고 dd 브랜치에서 작업을 하고 있다면 

  나의 HAED는 dd 라는 브랜치에 있다고 알려줍니다. 

