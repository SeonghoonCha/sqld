**SQL 기본**
1. 다음 중 함수명과 그에 대한 설명으로 올바르지 않은 것은?
    ㄱ. LOWER - 문자열의 알파벳 문자를 소문자로 바꾸어 준다.
    ㄴ. TRUNC - 숫자를 소수 m+1자리에서 반올림하여 리턴한다.
    ㄷ. DATEPART - 날짜 데이터에서 년/월/일 데이터를 출력할 수 있다.
    ㄹ. CAST - expression을 목표데이터 유형으로 변환한다.
    
2. 다음 중 단일 행의 특징으로 올바른 것은?
    ㄱ. SELECT, WHERE, ORDER BY, HAVING 절에 사용이 가능하다.
    ㄴ. 여러인자를 입력해도 단 하나의 결과만 리턴한다.
    ㄷ. 함수의 인자로 함수를 사용하는 함수의 중첩이 불가능하다.
    ㄹ. 하나의 인수만 가질 수 있다.
    
3. 다음 중 함수 사용에 대한 예상 결과로 옮바르지 않은 것은?
     ㄱ. LTRIM('xxxYYZZxYZ', 'x') - 'YYZZxYZ'
     ㄴ. CEIL(38.123) - 39
     ㄷ. NVL('Not-NUll', 'NVL-OK') - "NVL-OK"
     ㄹ. YEAR(SYSDATE) - 2019
     
 4. 다음 중 집계 함수의 설명으로 올바르지 않은 것은?
    ㄱ. 여러 행들의 그룹이 모여서 그룹당 단 하나의 결과를 돌려주는 함수이다.
    ㄴ. GROUP BY 절은 행들을 소그룹화 한다.
    ㄷ. SELECT 절, HAVING 절, ORDER BY 절에 사용할 수 있다.
    ㄹ. 디폴트로 DISTINCT 옵션이 되어있다.
   
5. POSITION 컬럼이 'FW'일 때 1, 아닐 경우 0을 출력하는 명령어를 simple_case_expression으로 표현하여라


6. 다음 중 GROUP BY에 대한 설명으로 올바르지 않은 것은?
    ㄱ. GROUP BY절에서는 SELECT 절과 달리 ALIAS 명을 사용할 수 없다.
    ㄴ. WHERE 절은 전체 데이터를 GROUP으로 나눈 후에 행들을 제거시키므로 HAVING을 사용하는 것이 효율적이다.
    ㄷ. HAVING 절은 GROUP BY 절의 기준 항목이나 소그룹의 집계 함수를 이용한 조건을 표시할 수 있다.
    ㄹ. HAVING 절이 GROUP BY절 위에 선언되어도 큰 문제는 없다.    

7. 선수 테이블에서 선수들의 이름, 포지션, 백넘버를 출력하는데 사람 이름을 올림차순으로 정렬하여 출력하는 명령어는?


8. SELECT 문장의 실행 순서를 나열하여라
    a. SELECT
    b. FROM
    c. WHERE
    d. GROUP BY
    e. HAVING
    f. ORDER BY
    
9. 사원 테이블에서 급여가 높은 2명에 대한 이름과 연봉을 내림차순으로 출력하는데 같은 급여를 받는 사원이 있으면 같이 출력하는 명령어는?


10. 다음 실행문에서 올바르지 않은 부분은?
    ㄱ. SELECT P.PLAYER_NAME 선수명, P.POSITION 포지션, T.REGION_NAME 연고지, T.TEAM_NAME 팀명, S.STADIUM_NAME 구장명
    ㄴ. FROM PLAYER P, TEAM T, STADIUM S
    ㄷ. WHERE P.TEAM_ID = T.TEAM_ID AND T.STADIUM_ID = S.STADIUM_ID AND 포지션 = "FW"
    ㄹ. ORDER BY P.TEAM_ID