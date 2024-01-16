# DOM SCRIPT (Document Object Model)

### 객체(Object)

- body / header / section 등을 객체(Object)라고 하고, 자바스크립트에서 조작을 할 수 있다.

  - class, id, element 등 html 에서 보여지는 모든 요소를 인터페이스 조작을 할 수 있다.

### 객체 메소드

- document.querySelector('.element')

- document.querySelectorAll('.elementGroup')

- data-index, data-id ...

  - element.setAttribute('data-id', 123)

  - element.getAttribute('data-id')

    - "123" 출력

  - 위와 같이 setAttribute, getAttribute 를 사용해도 되지만, element.dataset.id = 888 과 같이 dataset 속성을 사용해서 선언해 줄수도 있다.

    - char.dataset.title = "안녕!";

- document.createElement('p');

- element.innerHTML = "<a href="#">안녕</a> ??? ";

- element.appendChild(elementB);

- element.removeChild(elementB);

- element.classList.add('new-class'); (class를 기존 것에 추가한다.)

- element.className='new-class'; (class를 기존 것과 대체한다.)

- element.classList.remove('ilbuni'); (class 기존 것을 제거한다.)

- element.classList.toggle('ilbuni'); (class를 add/remove를 왔다갔다한다.)
