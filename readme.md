<h1>逆向破解方法收集</h1>

<h2>改变程序的判断</h2>

<p>返回true:</p>

<pre><code class="code-highlighted code-swift">mov eax, <span class="syntax-all syntax-constant">0x1</span></code></pre>

<p>返回false:</p>

<pre><code class="code-highlighted code-swift">mov eax, <span class="syntax-all syntax-constant">0x0</span>`</code></pre>

<h2>填平汇编代码, 使其不生效</h2>

<p><strong>Hopper Disassembler功能’NOP Region’:</strong></p>

<figure><img src="DraggedImage.png"/></figure>

<h2>x86-64 return（返回）机器码</h2>

<p><em>return 1</em>的X86-64机器码:</p>

<pre><code class="code-highlighted code-swift"><span class="syntax-all syntax-error">6A</span> <span class="syntax-all syntax-constant">01</span> <span class="syntax-all syntax-constant">58</span> C3</code></pre>

<h2>下断点运行调试判断</h2>


