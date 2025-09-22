This module will teach you the VERY basics of interacting with the command line!
The _command_ line lets you execute _commands_.
When you launch a terminal, it will execute a command line "shell", which will look like this:

```console
hacker@dojo:~$
```

This is called the "prompt", and it's prompting you to enter a command.
Let's take a look at what's going on here:

- The `hacker` in the prompt is the _username_ of the current user.
  In the pwn.college DOJO environment, this is "hacker".
- In the example above, the `dojo` part of the prompt is the _hostname_ of the machine the shell is on (this reminder can be useful if you are a system administrator who deals with many machines on a daily basis, for example).
  In the example above, the hostname is `dojo`, but in pwn.college, it will be derived from the name of the challenge you're attempting.
- We will cover what `~` means later :-)
- The `$` at the end of the prompt signifies that `hacker` is not an administrative user.
  In much later modules in pwn.college, when you learn to use exploits to become the administrative user, you will see the prompt signify that by printing `#` instead of `$`, and you'll know that you've won!

Anyways, the prompt awaits your command.
Move on to the first challenge to learn how to actually execute commands!

이 모듈은 너에게 명령어줄과 상호 작용하기 위한 가장 기본 사항들을 알려줄 것이다
명령어줄을 사용하여 명령어를 실행할 수 있다
터미널을 실행하면 다음과 같은 명령줄 쉘이 실행된다:

```console
hacker@dojo:~$
```

이것을 프롬프트라고 하며 명령을 입력하라는 메시지를 표시한다
여기에서 무슨 일이 일어나고 있는지 살펴보자:

- 프롬프트의 해커는 현재 사용자의 _username_이다
pwn.college DOJO 환경에서는 이것이 "해커"이다
- 위 예시에서 프롬프트의 dojo 부분은 셸이 켜져 있는 머신의 _hostname_이다 (이 알림은 많은 머신을 다루는 시스템 관리자라면 유용할 수 있다)
 위 예시에서 호스트 이름은 'dojo'이지만 pwn.college에서는 시도하는 도전의 이름에서 파생된다
- '~'의 의미는 나중에 다룬다 :-)
- 프롬프트 끝에 있는 '$'는 해커가 관리 사용자가 아님을 의미한다.
훨씬 나중에 pwn.college 모듈에선 익스플로잇을 사용해 관리 사용자가 되는 방법을 배울때 다음과 같은 작업을 수행한다

어쨌든 프롬프트가 당신의 명령을 기다리고 있다
첫번째 도전 과제로 넘어가면 실제로 명령 실행하는 방법을 배울 수 있다

2025년 9월 9일 결석 변경 희망합니다
