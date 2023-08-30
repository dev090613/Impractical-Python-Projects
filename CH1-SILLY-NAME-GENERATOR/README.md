#### 본 챕터에서 다시 확인할 내용들 기록



- 목표: “Randomly generate funny sidekick names using Python code that conforms to
  *established style guidelines.*” 

  (수립된 스타일 가이드 라인에 맞춰 파이썬 코드로 재치있는 무작위 조수 별명 생성하기)



- “The default for the print() function is the standard output, but with 
  the sys module loaded, you can redirect the output to the error channel, with 
  its trademark red coloring, using the file parameter: print(something, file=sys.stderr).”

  print() 함수의 기본값은 표준 출력이지만 sys 모듈이 로드된 상태라면 file 파라미터: print(출력할 것, 
  file=sys.stderr)를 이용해 빨간 색이 트레이드마크인 에러 채널로 출력을 리다이렉트할 수 있다.



- “If you find you’ve hacked your way into frustration, it may be because you didn’t take the time to write pseudocode.”

  만약 당신이 좌절감에 빠졌다면, 의사 코드 작성에 시간을 할애하지 않았기 때문일지도 모른다.



- 본 프로젝트의 Pseudo Code

  ~~~pseudocode
  Load a list of first names
  Load a list of surname
  
  Choose a first name at random
  Assign the name to a variable
  
  Choose a surname at random
  Assign the name to a variable
  
  print the name to the Screen in ortder and in red font
  Ask the user to quit or play again
  
  If the user play again:
  	Repeat
  else:
  	end and exit
  ~~~



- `chmod u+x ./pseudonyms.py`
  - u, g, o + r, w, x



- PEP 8 (https://www.python.org/dev/peps/pep-0008/) sets standards for naming conventions; use of blank lines, tabs, and spaces; maximum line length; comments; and so on. The goal is to improve the readability of code and make it consistent across a wide spectrum of Python programs.
