### Credit to StyleS*** (what a name) on codepen - https://codepen.io/EvyatarDa/pen/BaPgdgY

 ## New Techniques
-  background with gradients can be very powerful. It can be chained out creating the effect over and over on the same element. 

````
```
	background:
		
		/* Beak */
		conic-gradient( from -45deg at 50% 100%,
			#f7c21a 90deg,
			transparent 90deg
		) 50% 50% / 2.4em 1.2em,
		
		/* Right Eye */
		radial-gradient( ellipse 100% 100%,
			#96ee1e 25%,
			transparent 50%
		) right 22% top 40% / .7em .7em,
		
		radial-gradient( ellipse 100% 100%,
			#f6fafd 35%,
			transparent 50%
		) right 28% top 32.5% / 1.2em 1.2em,
		
		radial-gradient( ellipse 100% 100%,
			#310000 29%,
			#408407 30%,
			#408407 34%,
			rgba(0,0,0,.6) 44%,
			#ade546 45%,
			#ade546 49%,
			transparent 50%
		) right 20% top 30% / 4.2em 4.2em,
		
		/* Left Eye */
		radial-gradient( ellipse 100% 100%,
			#96ee1e 25%,
			transparent 50%
		) left 31% top 40% / .7em .7em,
		
		radial-gradient( ellipse 100% 100%,
			#f6fafd 35%,
			transparent 50%
		) left 22.5% top 32.5% / 1.2em 1.2em,
		
		radial-gradient( ellipse 100% 100%,
			#310000 29%,
			#408407 30%,
			#408407 34%,
			rgba(0,0,0,.6) 44%,
			#ade546 45%,
			#ade546 49%,
			transparent 50%
		) left 20% top 30% / 4.2em 4.2em,
		
		/* Bottom Shadow */
		linear-gradient(
			transparent 20%,
			rgba(0,0,0,.2)
		) left 50% bottom 0 / 100% 40%,
		
		/* Belly */
		radial-gradient( ellipse 100% 100%,
			#95d430 49%,
			transparent 50%
		) left 50% bottom -1em / 11em 7.5em,
		
		/* Body */
		linear-gradient(
			#c9ea81 -5%,
			#72c400 70%
		);
```
````