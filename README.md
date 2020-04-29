# 2020OSS_team
## CRUD Mini Project

<mini Project 주제>
  CRUD를 이용한 도서관 도서관리 시스템

<CRUD 도서관리 시스템의 기능>
  도서관리 시스템으로 등록된 도서를 관리할 수 있게한다 
  1. Create: 책을 도서관리 시스템에 등록한다 (반납)
  2. Read: 등록된 도서목록을 조회한다
  3. Update: 등록된 도서정보를 수정한다
  4. Delete: 등록된 도서를 대출처리한다
  5. Save: 도서목록을 저장한다
  6. Search: 해당도서를 검색한다

<Team member>
  김경록
  유수민

<Part in charge>
  CRUD, Menu, sort 구현: 김경록
    int selectMenu(); 
    int addBook(Book *b); 
    void readBook(Book b);
    int updateBook(Book *b);
    int deleteBook(Book *b); 
    void listBook(Book *b, int count); 
    int selectBookNum(Book *b, int count); 
    int sortBook(Book *b, int count);
    
  save load search 구현: 유수민
    void saveBookList(Book *b, int count);
    int loadBookList(Book *b); 
    void searchBookName(Book *s, int count); 
