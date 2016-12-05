# ResponseLayout
移动端布局通用解决方案
<pre style="max-width: 100%;"><code class="html hljs xml" codemark="1"><span class="hljs-meta">&lt;!DOCTYPE html&gt;</span>
<span class="hljs-tag">&lt;<span class="hljs-name">html</span> <span class="hljs-attr">lang</span>=<span class="hljs-string">"en"</span>&gt;</span>
<span class="hljs-tag">&lt;<span class="hljs-name">head</span>&gt;</span>
	<span class="hljs-tag">&lt;<span class="hljs-name">meta</span> <span class="hljs-attr">charset</span>=<span class="hljs-string">"UTF-8"</span>&gt;</span>
	<span class="hljs-tag">&lt;<span class="hljs-name">meta</span> <span class="hljs-attr">name</span>=<span class="hljs-string">"viewport"</span> <span class="hljs-attr">content</span>=<span class="hljs-string">"width=device-width, minimum-scale=1.0, maximum-scale=1.0"</span>&gt;</span>
	<span class="hljs-tag">&lt;<span class="hljs-name">title</span>&gt;</span>移动端通用布局解决方案<span class="hljs-tag">&lt;/<span class="hljs-name">title</span>&gt;</span>
	<span class="hljs-tag">&lt;<span class="hljs-name">style</span>&gt;</span><span class="css">
		<span class="hljs-selector-class">.HolyGrail-body</span> {  
		    <span class="hljs-attribute">display</span>: flex;
			<span class="hljs-attribute">flex</span>: <span class="hljs-number">1</span> <span class="hljs-number">0</span> auto; <span class="hljs-comment">/* 2 */</span>
			<span class="hljs-attribute">flex-direction</span>: column;
			<span class="hljs-attribute">padding</span>: <span class="hljs-number">1em</span>;
		}
		<span class="hljs-selector-class">.HolyGrail-content</span> {  
		    <span class="hljs-attribute">margin-top</span>: <span class="hljs-number">1em</span>;
		}
		<span class="hljs-selector-class">.HolyGrail-nav</span>, <span class="hljs-selector-class">.HolyGrail-footer</span> { 
			<span class="hljs-attribute">padding</span>: <span class="hljs-number">1em</span>;
  			<span class="hljs-attribute">border-radius</span>: <span class="hljs-number">3px</span>;
		    <span class="hljs-attribute">flex</span>: <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">1em</span>;
		    <span class="hljs-attribute">background</span>: <span class="hljs-built_in">rgba</span>(147, 128, 108, 0.1);
		}
		<span class="hljs-selector-class">.HolyGrail-nav</span> {  
		    <span class="hljs-attribute">order</span>: -<span class="hljs-number">1</span>;
		}
		@<span class="hljs-keyword">media</span> (min-width: <span class="hljs-number">768px</span>) { 
		    <span class="hljs-selector-class">.HolyGrail-body</span> {
			    <span class="hljs-attribute">flex-direction</span>: row;
			}
		  	<span class="hljs-selector-class">.HolyGrail-content</span> {
		    	<span class="hljs-attribute">flex</span>: <span class="hljs-number">1</span>;
		    	<span class="hljs-attribute">padding</span>: <span class="hljs-number">0</span> <span class="hljs-number">1em</span>;
		    	<span class="hljs-attribute">margin</span>: <span class="hljs-number">0</span>;
		  	}
			<span class="hljs-selector-class">.HolyGrail-nav</span>, <span class="hljs-selector-class">.HolyGrail-footer</span> {
			    <span class="hljs-attribute">flex</span>: <span class="hljs-number">0</span> <span class="hljs-number">0</span> <span class="hljs-number">12em</span>;
			}
		}
	</span><span class="hljs-tag">&lt;/<span class="hljs-name">style</span>&gt;</span>
<span class="hljs-tag">&lt;/<span class="hljs-name">head</span>&gt;</span>
<span class="hljs-tag">&lt;<span class="hljs-name">body</span>&gt;</span>
	<span class="hljs-tag">&lt;<span class="hljs-name">main</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"HolyGrail-body"</span>&gt;</span>
      <span class="hljs-tag">&lt;<span class="hljs-name">article</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"HolyGrail-content"</span>&gt;</span>
        哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈
        哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈
        哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈
        哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈
        哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈
        哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈
        哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈
        哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈
        哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈
        哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈
        哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈
        哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈
        哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈
        哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈
        哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈
        哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈
      <span class="hljs-tag">&lt;/<span class="hljs-name">article</span>&gt;</span>
      <span class="hljs-tag">&lt;<span class="hljs-name">nav</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"HolyGrail-nav"</span>&gt;</span>
        <span class="hljs-tag">&lt;<span class="hljs-name">strong</span>&gt;</span>导航栏<span class="hljs-tag">&lt;/<span class="hljs-name">strong</span>&gt;</span>
      <span class="hljs-tag">&lt;/<span class="hljs-name">nav</span>&gt;</span>
      <span class="hljs-tag">&lt;<span class="hljs-name">aside</span> <span class="hljs-attr">class</span>=<span class="hljs-string">"HolyGrail-footer"</span>&gt;</span>
        <span class="hljs-tag">&lt;<span class="hljs-name">strong</span>&gt;</span>底部<span class="hljs-tag">&lt;/<span class="hljs-name">strong</span>&gt;</span>
      <span class="hljs-tag">&lt;/<span class="hljs-name">aside</span>&gt;</span>
    <span class="hljs-tag">&lt;/<span class="hljs-name">main</span>&gt;</span>
<span class="hljs-tag">&lt;/<span class="hljs-name">body</span>&gt;</span>
<span class="hljs-tag">&lt;/<span class="hljs-name">html</span>&gt;</span></code></pre><p><br></p>
