# React Animation Suite

## Finally an animation library which is developer friendly!
This library is unopinionated about what should be the theory of animation, rather it focuses on how it should be implemented in React.

## Usage
#### Install
    npm i react-animation-suite -g
        OR
    yarn add react-animation-suite

#### Importing
    import { Slider } from "react-animation-suite"
        OR
    import { Slider } from "react-transition-suite/dist/lib/Slider"
    
#### Using
Say you component had JSX like this:

    <div className="container">
        <WannabeSlider {...props} />
    </div>
    
Now you can slide the WannabeSlider almost like this:
    
    <div className="container">
        <Slider {...sliderProps}>
            <WannabeSlider {...props} />
        </Slider>
    </div>
    

## Problem Statement
  - Animation libraries are very opinionated about how animations should be done, how to implement timings, stiffness, etc.
  - Almost all libraries require a lot of learning before implementing. It's not like you know react and you have animation component from library, then you can simply use it just like that.
  - Animation libraries tend to do magic underneath, reading them is a difficult task if you want to know their internal working. So it is difficult to contribute in them.
  - Implementing many animation libraries requires to be implemented from starting. Using a library in the middle or end of development is very tough.
 
#### This library is here to solve all these problems. Even if you are contributing, which is what all of us should do, you must think of solving all those above problems.

# Features
  - For now we have only Slider component.
  
### Tech

* [ReactJS] - Obvious!
* [React Transition Group] - This library internally uses react transition group. And rather than making a React wrapper of current library, we try to create animations on pure css or javascript.
* [Typescript] - This won't be downloaded as dependency, but just to point out - we are using typescript and we would suggest other developers to use typescript.

And of course Dillinger itself is open source with a [public repository][dill]
 on GitHub.


### Development
Want to contribute? Great!

Please read `CONTRIBUTING.md`.

#### Special thanks to [TypeScript library starter](https://github.com/alexjoverm/typescript-library-starter) for easing the process to create a library in typescript.


   [ReactJS]: <https://reactjs.org/>
   [React Transition Group]: <https://reactcommunity.org/react-transition-group/>
   [Typescript]: <https://www.typescriptlang.org/>
