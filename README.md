# React UseEffect setInterval memory leak
This repository demonstrates a common mistake in React: using setInterval within useEffect without proper cleanup. This leads to a memory leak because the interval continues to run even after the component is unmounted.

The `bug.js` file shows the problematic code. The `bugSolution.js` file provides a corrected version that addresses the memory leak using the cleanup function provided by useEffect.