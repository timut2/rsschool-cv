
## Full Name: 
Timur Polenov
## Contact Information: 
* Phone numuber: +79859048038
* Telegram: @polenovt
* email: Timur.polenov@gmail.com
## Brief Self-Introduction:
I am interested in improving my knowlendges and abilities in web development
## Skills :
* Python
* HTML
* CSS
* JavaScript 
* React 
## Code Examples:
```
import './App.css';
import Header from './Components/Header';
import Main from './Components/Main';
import Footer from './Components/Footer';
import Puzzle from './Components/Puzzle'; // Импортируем компонент
import { useState } from 'react';

function App() {
  const [isPuzzleSolved, setIsPuzzleSolved] = useState(false); // Состояние для контроля решения головоломки

  return (
    <div>
      {!isPuzzleSolved ? (
        <Puzzle onSolve={() => setIsPuzzleSolved(true)} /> // Передаем функцию для решения головоломки
      ) : (
        <>
          <Header />
          <div className="main-container"> 
            <Main />
            <Main />
            <Main />
            <Main />
          </div>
          <Footer />
        </>
      )}
    </div>
  );
}

export default App;
```
## Work Experience : 
* Making online reports for Laboratory. Big SQL queries and a little bit of JavaScript
* Right now i work in company that provides technical support for government projects. 
## Education : 
* Bachelor in Moscow Power Engineering Institute with specialty in Informatics and Computer Science
* Master's student in Moscow University named after S.Y. Witte with specialty in Applied Information Science
## Languages:
Russian Native
English B2\