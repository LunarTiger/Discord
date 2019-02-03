<p>Here I have a backup of my plugins and themes for Better Discord.<br>If you do decide to use them, just know they may or may not be up to date.</p>
<h3 id='folders'>Direct Downloads:</h3>
<table>
	<tr>
		<th id='plugins'><a href='plugins.7z'>Plugins</a></th>
	</tr>
	<tr>
		<th id='themes'><a href='themes.7z'>Themes</a></th>
	</tr>
</table>
<br>
<h3 id='files'>Delete All Messages Script:</h3>
<pre id="delete-all-messages" style="text-align:left; background:transparent; color: green;max-width:100%;max-height:95%;height:800px;width:480px;border: 4px solid #006900;margin: auto;"></pre>
<script>
	fetch('{{ site.github.url }}/delete-all-messages.js')
	.then(body=>body.text())
	.then(body=>{
		document.getElementById('delete-all-messages').innerText = body;
	})
</script>