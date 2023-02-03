# test
깃허브 사용법을 연습합니다.

여기에 원하는 내용을 입력하세요.

소스에 대한 간단한 소개글을 작성합니다.
***
# 첫 번째 제목
+ 안녕하세요.
- 권정민입니다.
* 반가워요.

+ 안녕하세요.
+ 권정민입니다.
  + 반가워요.

**안녕**하세요.

__안녕__ 하세요.

_권정민_ 입니다.

*권정민*입니다.

***권정민***입니다.

___권정민___ 입니다.

~~반가워요.~~

---
## 두 번째 제목
### 세 번째 제목
#### 네 번째 제목
##### 다섯 번째 제목

***

# 소스코드 삽입하기
1.한 줄 소스 코드
`function add(x, y){ return x + y }`
2. 여러 줄 소스코드
```java
Scanner scan = new Scanner(System.in);
	public DeleteTest() {
	}
	public void start() {
		try {
			System.out.print("삭제할 사원명: ");
			String ename = scan.nextLine();
			getConnection();
			sql = "delete from emp2 where ename=?";
			pstmt = con.prepareStatement(sql);
			pstmt.setString(1, ename);
			
			int result = pstmt.executeUpdate();
			if(result>0) {// 삭제된 경우
				System.out.println(ename + "사원의 정보가 삭제되었습니다.");
			}else {// 삭제된 레코드가 없을 때
				System.out.println("삭제 정보가 없습니다.");
			}
		}catch(Exception e) {
			e.printStackTrace();
		}finally {
			dbClose();
		}
	}
	public static void main(String[] args) {
		new DeleteTest().start();
	}
```

***

<https://www.naver.com/>

[네이버](https://www.naver.com/)

[구글](https://www.google.co.kr/), "검색 사이트")
