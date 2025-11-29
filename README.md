# ⚛️ React Senior Interview Questions (125+ Curated Q&A)

This repository contains a hand-picked set of advanced React topics that commonly appear in senior interviews, real-world architecture discussions, and system design rounds.

## 📘 What You’ll Find
- Hooks, lifecycle, performance, SSR, hydration
- Real-world scenarios and edge cases
- Deep-dive React hooks & lifecycle mechanics
- Real-world scenario-based questions

## 🧠 Sample Questions (Free)

1. What happens if you omit keys in a list?
Ans. React will fall back to using array indexes, which can lead to inefficient re-renders and bugs in dynamic lists (e.g., incorrect input focus or animations).

2. What is the difference between useMemo and useCallback?
Ans. useMemo memoizes values, while useCallback memoizes functions. Both optimize performance by preventing unnecessary recalculations or re-creations.

3. How does React decide when to re-render a component?
Ans. React re-renders when state or props change. It compares previous and current values using shallow comparison. Memoization can prevent unnecessary re-renders.

4. What is the difference between useEffect(() => {}, []) and useEffect(() => {})?
Ans. The first runs only once after mount. The second runs after every render. The dependency array controls when the effect runs.

5. What problem does the Context API solve?
Ans. It avoids prop drilling by allowing global state sharing across deeply nested components. Useful for themes, auth, or language settings.

Full set includes 125+ questions with detailed answers. 

## 📥 Download the Full Guide(PDF)
If you want the complete curated collection:
https://codeymazestore.gumroad.com/l/wihfnj

## 💡 Who It's For
- Senior React developers preparing for interviews
- Hiring managers evaluating candidates
- Educators and mentors building curriculum

---

Feel free to fork, share, or contribute!
