# Color Generator App
The design idea is taken from one of courses in udemy

Learnings:
  
1) How to use Values.js library:  https://github.com/noeldelgado/values.js
2) Conditional rendering of css, by adding conditional class name. 
   e.g.  <article className={error ? 'error' : null}> </article>
3) Dynamic inline styling:
	<article style={{ backgroundColor: `rgb(${bcg})` }}>
4) Copy text from clipboard on click functionality (navigator.clipboard.writeText('your text');
