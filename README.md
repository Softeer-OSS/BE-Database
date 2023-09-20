# BE-Database
A simple relational database based on [Stanford CS346 RedBase](https://web.stanford.edu/class/cs346/2015/), based on Java 11.

## Members

<table>
    <thead>
        <tr>
            <th style="text-align:center;"><a href="https://github.com/Chocochip101">권기호</a></th>
            <th style="text-align:center;"><a href="https://github.com/kwYoohae">유해찬</a></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><img src="https://avatars.githubusercontent.com/u/73146678?v=4" width="250"/></td>
            <td><img src="https://avatars.githubusercontent.com/u/74089271?v=4" width="250"/></td>
        </tr>
    </tbody>
</table>

## Features
- 인덱싱: B+Tree 기반으로 단일 테이블 쿼리와 테이블 조인을 빠르게 검색합니다.
- Durability: 트랜잭션이 완료되면 영구히 반영됩니다.
- SQL: 기본 DDL (create table, drop table, create index, drop index)과 DML (insert, delete, update, select) 구문을 지원합니다.

## Plans
TBD

## TODO
- [ ] Paged File Module (PF) enables higher-level modules to perform efficient file I/O in terms of pages.

- [ ] Record Management Module (RM) manages the storage of unordered records.

- [ ] Indexing Module (IX) manages persistent indexes over unordered data records stored in record files.

- [ ] System Management Module (SM) handles the data definition language (DDL), including create table, drop table, create index, drop index statements.

- [ ] Query Language Module (QL) handles the data manipulation language (DML), including insert, delete, update, select statements.

- [ ] SQL Parser translates a raw SQL statement into an Abstract Syntax Tree (AST), which is further interpreted and executed by the controller.

- [ ] JDBC connection that can Java applications enable communication between the application and the database server.

## REF
https://cs.stanford.edu/people/chrismre/cs346/project.html