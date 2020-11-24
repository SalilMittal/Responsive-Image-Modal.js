# Simple-Javascript-Image-Modal
<strong>Responsive-Image-Modal.js</strong> is an easy to use fully responsive image modal for your websites. It uses vanilla JavaScript and CSS. No more 3 lines to get started.</p>
<p></p>
<h2>How To Use:</h2>
<p><u>index.html</u></p>
<pre>
	
	<span>&lt;!DOCTYPE html&gt;</span>
<span>&lt;<span>html</span> <span>lang</span>=<span>"en"</span>&gt;&lt;<span>head</span>&gt;&lt;<span>meta</span> <span>charset</span>=<span>"UTF-8"</span>&gt;&lt;<span>meta</span> <span>name</span>=<span>"viewport"</span> <span>content</span>=<span>"initial-scale=1.0, maximum-scale=1.0, user-scalable=no"</span> /&gt;&lt;<span>title</span>&gt;</span>Document<span>&lt;/<span>title</span>&gt;&lt;<span>link</span> <span>rel</span>=<span>"stylesheet"</span> <span>href</span>=<span>"css/modal.css"</span>&gt;&lt;/<span>head</span>&gt;&lt;<span>body</span>&gt;&lt;<span>div</span> <span>class</span>=<span>"img-modal"</span>&gt;&lt;/<span>div</span>&gt;</span> <span>&lt;!--Create a div for modal --&gt;</span>

      <span>&lt;<span>img</span> <span>src</span>=<span>"https://i.pinimg.com/736x/ce/c0/74/cec074ab85ddb1b716c8ea9ed2a79d4f.jpg"</span> <span>alt</span>=<span>""</span>&gt;&lt;/<span>body</span>&gt;&lt;<span>script</span> <span>src</span>=<span>"js/modal.js"</span>&gt;&lt;/<span>script</span>&gt;&lt;<span>script</span>&gt;</span>
      initModal(<span>"img-modal"</span>); <span>//Initialize Modal by class of modal</span>
      addModal(<span>document</span>.querySelectorAll(<span>"img"</span>)); <span>// Add Modal to Array of Image/Images</span><span>&lt;/<span>script</span>&gt;</span>
<span>&lt;/<span>html</span>&gt;</span>

</pre>
<p></p>
<h2>Functions:</h2>
<p><code>initModal(<em>className</em>)</code> : Initialize Modal with parameter as class name of modal div - call this at the beginning of your script</p>
<p><code>addModal(<em>images</em>)</code> : Call the function with image(s) as a node array. Preferably use <code>document.querySelector()</code></p>
<p>or <code>document.querySelectorAll()</code></p>
<p></p>
<p>Going to add customizable features soon...</p>
<p></p>
<h2>Contributions:</h2>
<p></p>
<p><a href="https://github.com/SalilMittal">Salil Mittal</a></p>
