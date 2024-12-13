React Concepts

Avoiding component Function Execution with memo():

    - Memo - Take a look at drops of component function, and when ever, if whenever the component function would normally execute again for example, if the app component execute again as a state changed Of the entered number, this tries to read under the compound, the component of counter, which has the prop of initial value which was not altered, but you are simply wasting react execution by executing or rendering again to avoid this one way around is to use affect hook or there is a new one called memo that can be used at the functional level of the component which checks if the old prop has changed with respect to new prop that was passed and hold the execution or rerdering of the component again

    images before - screenshots/without-memo.png and after - screenshot.with-memo.png use of memo

    - dont over wrap the or over use the memo, instead use the memo at as higher level as possible
    - dont use at the functions where the props changes too frequently to avoid uneccessary computation

    When to Use
    - Use React.memo when you want to optimize rendering for functional components with stable props.
    - Use useEffect when you need to perform side effects like data fetching, subscriptions, or DOM manipulation.
