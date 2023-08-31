## React

- Single-page applications - as opposed to server-side rendering
- Reactivity - useEffect 



Standing on the shoulders of giants

- Styled Components
- 3rd-party Libraries (Example: MUI)
	- adding requirements to package.json
	- versioning
	- version incompatibilities
	- choosing alternatives (e.g. )
- UI Patterns:
	- Modal Dialog


CSS
- [collapsing margins](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_box_model/Mastering_margin_collapsing) - quite a nitpick
- [using rem instead of px](https://levelup.gitconnected.com/solving-all-css-layout-issues-any-screen-any-root-font-size-without-js-62349644a71e) -- quite a long article





Random Stuff
- Why is it better to use an named function expression? [so discussion](https://stackoverflow.com/questions/15336347/why-use-named-function-expressions) 




## Intermezzo: Semantic HTML

Semantic HTML are a mew set of HTML tags that aim to be more expressive than just divs with classes ([article](https://www.freecodecamp.org/news/semantic-html5-elements/)).

![](images/semantic_html.png)

Compare the following two snippets:

```text
<div id="header"></div>
<div class="section">
	<div class="article">
		<div class="figure">
			<img>
			<div class="figcaption"></div>
		</div>
	</div>
</div>
<div id="footer"></div>
```

vs. 

```text
<header></header>
<section>
	<article>
		<figure>
			<img>
			<figcaption></figcaption>
		</figure>
	</article>
</section>
<footer></footer>
```


# Javascript

[Client Side HTML form validation](https://developer.mozilla.org/en-US/docs/Learn/Forms/Form_validation)
