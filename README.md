* 번역자: Jhonghee Park (jhonghee@gmail.com, jhonghee.park@ey.com)

# 러스트 프로그래밍 언어
# The Rust Programming Language

환영! 이 책을 통해 여러분은 [러스트 프로그래밍 언어](rust)를 배우게 된다. 러스트는 다음과 같은 세가지 목표를 가지고 있는 시스템 프로그래밍 언어이다: 안정성, 속도, 그리고 동시성. 가비지 컬렉터(garbage collector)없이도 이러한 목표를 유지하며, 다른 언어에서 잘 해결하지 못하는 여러 사용 사례에 대한 유용한 언어로 쓰일 수 있다: 예를 들면 다른 언어에 임베딩 되는 경우나, 저장공간과 실행시간에 대해 까다로운 요구사항이 있는 프로그램이라던지, 디바이스 드라이버나 운영체제와 같은 로우레벨 코드를 작성해야 하는 경우들이다. 이와 비슷한 영역을 목표로 하는 현존 언어들을 여러 컴파일-타임 검사를 통해 개선하면서 런타임에 불필요하게 추가되는 간접비용들이 없애면서도 모든 데이터 레이스(data races)를 제거한다. 러스트는 또한 하이-레벨 언어에 버금가는 추상화를 지원하면서도 '제로 비용 추상화(zero-code abstractions)'를 달성하려는 목표를 가지고 있다. 심지어 그런 시도내에서도 로우-레벨 언어에 손색없는 제어의 정확성을 여전히 허용한다.  

Welcome! This book will teach you about the [Rust Programming Language][rust].
Rust is a systems programming language focused on three goals: safety, speed,
and concurrency. It maintains these goals without having a garbage collector,
making it a useful language for a number of use cases other languages aren’t
good at: embedding in other languages, programs with specific space and time
requirements, and writing low-level code, like device drivers and operating
systems. It improves on current languages targeting this space by having a
number of compile-time safety checks that produce no runtime overhead, while
eliminating all data races. Rust also aims to achieve ‘zero-cost abstractions’
even though some of these abstractions feel like those of a high-level language.
Even then, Rust still allows precise control like a low-level language would.

[rust]: https://www.rust-lang.org

"러스트 프로그래밍 언어"는 다음과 같이 나뉜다. 소개의 글이 우선 나오고 그 다음으로:

“The Rust Programming Language” is split into chapters. This introduction
is the first. After this:

* [시작하면서][gs] - 러스트 개발을 위해 컴퓨터 셑업하기
* [튜토리얼: 추측 게임][gg] - 소규모 프로젝트로 러스트 배우기.
* [구문과 기호][ss] - 러스트를 잘게 나눈 작은 조각들을 통해 익히기.
* [효과적인 러스트][er] - 훌륭한 러스트 코딩을 위한 하이-레벨 컨셉들.
* [최신 러스트][nr] - 안정된 빌드에 아직 포함되지 않은 최신 기능들.
* [용어집][gl] - 책에 이용된 용어집.
* [서지][bi] - 러스트에 영향을 준 배경이야기, 러스트에 대한 페이퍼.

* [Getting started][gs] - Set up your computer for Rust development.
* [Tutorial: Guessing Game][gg] - Learn some Rust with a small project.
* [Syntax and Semantics][ss] - Each bit of Rust, broken down into small chunks.
* [Effective Rust][er] - Higher-level concepts for writing excellent Rust code.
* [Nightly Rust][nr] - Cutting-edge features that aren’t in stable builds yet.
* [Glossary][gl] - A reference of terms used in the book.
* [Bibliography][bi] - Background on Rust's influences, papers about Rust.

[gs]: getting-started.html
[gg]: guessing-game.html
[er]: effective-rust.html
[ss]: syntax-and-semantics.html
[nr]: nightly-rust.html
[gl]: glossary.html
[bi]: bibliography.html

### 기여
### Contributing

이 책의 소스 코드는 [GitHub][book]에서 찾아 볼 수 있다.

[book]: https://github.com/rust-lang/rust/tree/master/src/doc/book
