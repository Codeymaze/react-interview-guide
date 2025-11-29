# ⚛️ React Senior Interview Questions (125+ Curated Q&A)

This repository contains a hand-picked set of **advanced React interview topics** commonly asked in senior engineering rounds, architecture discussions, and real-world problem-solving scenarios.

---

## 📘 What You’ll Find
- Advanced Hooks & lifecycle behavior  
- Performance optimization patterns  
- SSR, hydration, streaming  
- Real-world scenarios and edge cases  
- Concurrency, transitions, React 18 internals  
- Practical questions asked in top tech interviews  

---

## 🧠 Sample Questions (Free)

### **1. What happens if you omit keys in a list?**  
React will fall back to array indexes, causing inefficient re-renders and UI bugs in dynamic lists (e.g., wrong item focus, broken animations).

### **2. Difference between `useMemo` and `useCallback`?**  
- `useMemo` memoizes values.  
- `useCallback` memoizes functions.  
Both prevent unnecessary recalculation/re-creation and help with performance.

### **3. How does React decide when to re-render a component?**  
React re-renders when state or props change. It uses shallow comparison. Memoization (`React.memo`, `useMemo`, `useCallback`) prevents unnecessary renders.

### **4. `useEffect(() => {}, [])` vs `useEffect(() => {})`**  
- With `[]`: runs *once* after mount.  
- Without `[]`: runs *after every render*.  
The dependency array controls effect execution.

### **5. What problem does the Context API solve?**  
It prevents prop drilling by allowing global/shared state across nested components. Often used for theme, auth, locale, etc.

---

👉 *The full set includes **125+ expert-level questions** with detailed answers and architecture insights.*

---

## 📥 Download the Full Guide (PDF)
If you want the complete curated collection:  
**https://codeymazestore.gumroad.com/l/wihfnj**

---

## 💡 Who It's For
- Senior React developers preparing for interviews  
- Hiring managers evaluating candidates  
- Educators and mentors building curriculum  

---

⭐ **If you find this useful, consider starring the repo!**

