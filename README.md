# react-webgame

소스코드 레포지토리입니다.

# svelte-webgame

https://github.com/makefullstack/svelte-webgame

# 6.로또

반복문은 별도 컴포넌트로 빼라

함수 컴포넌트(Ball.jsx)와 Hooks는 다르다

Lifecycle will 시리즈 중 componentWillUnmount말곤 전부 사라질 예정

자식 컴포넌트에 함수를 넘길 때는 useCallback을 꼭 선언해줘야 한다.

compnentDidMount() 효과만 낼 수 있는 편법이 있다. 6-6 거의 마지막

# 7.틱택토

변수를 export, import해서 Component 끼리 공유할 수 있다.(대박)

spread 연산자는 깊은 복사로 알고 있는데 동영상에서 거듭 얕은 복사라고 함.(https://hanamon.kr/javascript-shallow-copy-deep-copy/)

useEffect와 useRef로 Rendering을 추측할 수 있다.(최적화 시 필요)

반복문이 있는데에 memo를 쓰면 됨.

# ETC

찾아보니까 react-hot-loader 보다 react-refresh가 더 최신이라함 ㅡㅡ;;(https://url.kr/bcurwy)
