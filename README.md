# 💫 Markdown
![Markdown-mark svg](https://user-images.githubusercontent.com/118426836/202700027-0e732f94-45b9-421d-a803-81bbf4a96cd9.png)

## ✔목차
 1. 개요
 2. 문법 (Syntex)  
  
  
## 1. 개요
**마크다운(Markdown)** 은 기본 문법만 알고있다면 일반 텍스트 편집기에서도 손쉽게 작성 가능한 마크업 언어이다.  
HTML과 리치텍스트 (RTF) 등 서식 문서로 쉽게 변환되므로, 응용소프트웨어와 함께 배포되는 **README파일** 이나 온라인 게시물 등에 많이 사용된다.  
  
## 2. 문법 (Syntex)

### 2.1 제목 (Header)
```
   # This is a H1
   ## This is a H2
   ### This is a H3
   #### This is a H4
   ##### This is a H5
   ###### This is a H6
```  
![image](https://user-images.githubusercontent.com/118426836/202711021-ea05e2ff-7c35-4eee-a968-92cadeb27ea8.png)  
  
### 2.2 목록 (Lists)
번호 또는 기호 (+,*,-) 로 나태낼 수 있다.
```
   List A
   * Item 1 
   + Item 2
   - Item 3 

   List B 
   1. Item 1 
   1. Item 2 
   1. Item 3 
```  
![image](https://user-images.githubusercontent.com/118426836/202720508-ec3086a3-f2b8-4d66-8f41-d4edd8ecba9b.png)  
   
### 2.3 강조 (Emphasis)
``` 
   *italic lettering*  
   _also italic lettering_  
   **bold lettering**   
   __also bold lettering__  
   <u>underlined lettering</u>  
   <strike>lettering with strikethrough</strike>  
```  
![image](https://user-images.githubusercontent.com/118426836/202718461-03be8394-b666-43d2-bd72-7062c9826bc1.png)  
  
### 2.4 표 (Tables)
```
   | Title1(기본왼쪽정렬) | Title2(가운데정렬) | Title3(오른쪽정렬) |
   |---|:---:|---:|
   | content 1 | content 1 | content 1 |
   | content 12345 | content 12345 | content 12345 |
```  
![image](https://user-images.githubusercontent.com/118426836/202719533-dc52f774-0391-4037-a94d-2501fb48c14b.png)     
   
### 2.5 인용문 (BlockQuote)
```
   Example of a quote
   >warning : This text is Blockquotes by Markdown syntex.
   >>Blockquotes can also be nested
```  
![image](https://user-images.githubusercontent.com/118426836/202715859-b332acd8-2e0b-410b-8e16-4d754a067a14.png)  
  
### 2.6 링크 (Links)
```
   [Title](link)
   eg. [Google](https://google.com, "google link")  
   Title : <link>
   eg. 네이버 : <https://naver.com>
```
![image](https://user-images.githubusercontent.com/118426836/202719360-61a904a1-71f6-4e3b-9c6f-e6f356a0920f.png)  
  
### 2.7 이미지 (Images)
![이미지 alt명](url 링크) 
```
   ![이미지 alt명](url 링크) 
   ![Github logo](/images/markdown_logo.jpg)
```
![Markdown-mark svg](https://user-images.githubusercontent.com/118426836/202719142-e28c3e69-c611-442d-9da2-c7c37ddfa34c.png)  
  
### 2.8 뱃지 (Badge) 와 링크 추가

```markdown
<img src="https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=Laravel&logoColor=white">
```


💡 아이콘: <https://simpleicons.org/>


- 위 사이트에서 원하는 아이콘의 색상코드를 복사하여 ‘#’ 제외하고 입력


💡 뱃지에 링크 추가


```markdown
[<뱃지 추가 명령어>](URL)
```
  
