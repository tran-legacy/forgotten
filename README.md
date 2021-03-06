<h1 id="forgotten">forgotten</h1>

<p>A vim theme inspired by the <a href="https://oblotzky.github.io/sa-oblivion/">Oblivion keycap set</a> by oblotzky (which was inspired by the Oblivion tmTheme by Paolo Borelli).</p>

<h2 id="screenshots">screenshots</h2>

<table>
<tr><td align="center"><strong>forgotten-dark</strong></td><td align="center"><strong>forgotten-light</strong></td></tr>
<tr>
<td><img src="/img/screenshot-forgotten-dark.png" alt="screenshot of the forgotten-dark vim theme" width="288" /></td>
<td align="center"><img src="/img/screenshot-forgotten-light.png" alt="screenshot of the forgotten-light vim theme" width="288" /></td>
</tr>
</table>

<blockquote>
  <p>pictured font: <a href="http://input.fontbureau.com/">Input Mono Narrow</a> (1.2x line spacing)</p>
</blockquote>

<h2 id="setup">setup</h2>

<h3 id="installation">installation</h3>

<p>While vim themes can be installed manually (place <a href="https://github.com/nightsense/forgotten/tree/master/colors">theme file</a> in <code class="highlighter-rouge">~/.vim/colors/</code>), a <strong>plugin helper</strong> is recommended.</p>

<p>If you don’t have a preferred helper, consider trying <a href="https://github.com/junegunn/vim-plug">vim-plug</a>, which can be installed with:</p>

<div class="highlighter-rouge"><pre class="highlight"><code>curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
</code></pre>
</div>

<p>To install forgotten via vim-plug, add the following to the top of your <code class="highlighter-rouge">vimrc</code>:</p>

<div class="highlighter-rouge"><pre class="highlight"><code>call plug#begin('~/.vim/plugged')
Plug 'nightsense/forgotten'
call plug#end()
</code></pre>
</div>

<p>Then restart vim and run <code class="highlighter-rouge">PlugUpdate</code> (from the vim command line).</p>

<h3 id="activation">activation</h3>

<p>To activate the forgotten theme, add one of the following lines to your <code class="highlighter-rouge">vimrc</code>:</p>

<ul>
  <li><code class="highlighter-rouge">colorscheme forgotten-light</code></li>
  <li><code class="highlighter-rouge">colorscheme forgotten-dark</code></li>
</ul>

<p>Note that the <code class="highlighter-rouge">background</code> setting doesn’t affect this theme.</p>

<blockquote>
  <p>To assign themes to specific intervals of the day, try the <a href="https://github.com/nightsense/night-and-day">night-and-day</a> plugin.</p>
</blockquote>

<h2 id="terminal-vim">terminal vim</h2>

<p>See the <a href="https://github.com/nightsense/nightshell">nightshell</a> repository, which allows forgotten to be used in a variety of terminal applications.</p>

<h2 id="palette">palette</h2>

<p>forgotten consists of 8 theme-distinct <strong>base colours</strong>, which are used for most interface elements, and 8 standard <strong>accent colours</strong> (common to the “nightsense theme family”) used for syntax highlighting.</p>

<blockquote>
  <ul>
    <li>accent colour hues were selected at the scale of 1/12 (30°) colour wheel intervals
      <ul>
        <li>6 of these hues were fine-tuned with 1/6 subinterval adjustments</li>
      </ul>
    </li>
    <li>base colour hue was selected from among:
      <ul>
        <li>the 24 hues available at the scale of 1/24 (15°) colour wheel intervals</li>
        <li>the additional 6 aforementioned fine-tuned hues</li>
      </ul>
    </li>
    <li>discrete intervals were also used for tuning colour saturations (1/24) and values (1/12)</li>
    <li>the <a href="https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-contrast.html#visual-audio-contrast-contrast-73-head">ISO 3:1 contrast standard</a> is met by nearly all text/background combinations, exceptions being made for some transient-highlighted backgrounds (e.g. cursorcolumn, cursorline)</li>
  </ul>
</blockquote>

<table>
  <thead>
    <tr>
      <th style="text-align: right">base</th>
      <th style="text-align: center">light-background accents</th>
      <th style="text-align: left">dark-background accents</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/1d252b.png" height="24" width="42" /> <code class="highlighter-rouge">1d252b</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/eb3b3b.png" height="24" width="42" /> <code class="highlighter-rouge">eb3b3b</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/d45959.png" height="24" width="42" /> <code class="highlighter-rouge">d45959</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/303940.png" height="24" width="42" /> <code class="highlighter-rouge">303940</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/e07426.png" height="24" width="42" /> <code class="highlighter-rouge">e07426</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/c97b42.png" height="24" width="42" /> <code class="highlighter-rouge">c97b42</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/3f4b54.png" height="24" width="42" /> <code class="highlighter-rouge">3f4b54</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/ebbf3b.png" height="24" width="42" /> <code class="highlighter-rouge">ebbf3b</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/d4b659.png" height="24" width="42" /> <code class="highlighter-rouge">d4b659</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/6c7175.png" height="24" width="42" /> <code class="highlighter-rouge">6c7175</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/289e31.png" height="24" width="42" /> <code class="highlighter-rouge">289e31</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/5c8a60.png" height="24" width="42" /> <code class="highlighter-rouge">5c8a60</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/8e9194.png" height="24" width="42" /> <code class="highlighter-rouge">8e9194</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/289e8a.png" height="24" width="42" /> <code class="highlighter-rouge">289e8a</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/508a80.png" height="24" width="42" /> <code class="highlighter-rouge">508a80</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/b8bcbf.png" height="24" width="42" /> <code class="highlighter-rouge">b8bcbf</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/3083bf.png" height="24" width="42" /> <code class="highlighter-rouge">3083bf</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/5688ab.png" height="24" width="42" /> <code class="highlighter-rouge">5688ab</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/d7dde0.png" height="24" width="42" /> <code class="highlighter-rouge">d7dde0</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/8f69b5.png" height="24" width="42" /> <code class="highlighter-rouge">8f69b5</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/8b779e.png" height="24" width="42" /> <code class="highlighter-rouge">8b779e</code></td>
    </tr>
    <tr>
      <td style="text-align: right"><img src="http://www.colorhexa.com/f5fbff.png" height="24" width="42" /> <code class="highlighter-rouge">f5fbff</code> </td>
      <td style="text-align: center"><img src="http://www.colorhexa.com/e05e8a.png" height="24" width="42" /> <code class="highlighter-rouge">e05e8a</code> </td>
      <td style="text-align: left"><img src="http://www.colorhexa.com/c97591.png" height="24" width="42" /> <code class="highlighter-rouge">c97591</code></td>
    </tr>
  </tbody>
</table>

<p><img src="http://www.colorhexa.com/eb3b3b.png" height="24" width="42" />
<strong>Red</strong>, the colour of alarm, is used for <strong>warning elements</strong>, including error messages, misspellings, and diff deletions.</p>

<p><img src="http://www.colorhexa.com/e07426.png" height="24" width="42" />
<strong>Orange</strong> is the colour of fire, which serves as a preliminary to many practical activities. Orange is therefore used for <strong>preliminary elements</strong>, such as preprocessor commands (which prepare data to be handled by another program), incremental searching (that is, a search term in the process of being typed), titles, and miscapitalized words.</p>

<p><img src="http://www.colorhexa.com/ebbf3b.png" height="24" width="42" />
<strong>Yellow</strong>, the classic highlighting colour, is applied to elements that are not warnings yet should draw attention with high visibility. These <strong>highlighted elements</strong> include search results, task tags (<code class="highlighter-rouge">TODO</code>, <code class="highlighter-rouge">FIXME</code>…), and diff changes.</p>

<p><img src="http://www.colorhexa.com/289e31.png" height="24" width="42" />
<strong>Green</strong>, the colour that says “go ahead, proceed with the task at hand”, is used for <strong>action elements</strong>, such as statements (if/then, while/do, case…), mode indicators (insert, visual…), vim user prompts, and diff additions.</p>

<p><img src="http://www.colorhexa.com/289e8a.png" height="24" width="42" />
<strong>Teal</strong> is named after the “common teal”, a kind of duck, thus connecting this colour with the concept of “species”, which is a means of classifying life into very specific types. Teal is therefore used for specifying <strong>object types</strong>, such as data type (boolean, integer, string…) or storage class (static, volatile…), as well as mislocalized words (that is, words that are not misspelled but of the wrong type, namely a foreign locale type).</p>

<p><img src="http://www.colorhexa.com/3083bf.png" height="24" width="42" />
<strong>Blue</strong>, a colour of calm stability, is used for <strong>constants</strong>, which come in the form of boolean values, integers, floating-point numbers, characters, and strings.</p>

<p><img src="http://www.colorhexa.com/8f69b5.png" height="24" width="42" />
<strong>Purple</strong>, often associated with rare purple dyes historically produced for special works of art, is used for <strong>special text</strong>, including special characters (standalone or within syntax units), vim tags, and debugging statements. Rarely-used words are also marked, allowing the writer to consider whether such a specially uncommon word is appropriate.</p>

<p><img src="http://www.colorhexa.com/e05e8a.png" height="24" width="42" />
<strong>Pink</strong>, the colour of spring blossoms, is used for <strong>object names</strong>, including the names of variables and functions. To code is to bring countless objects blossoming into existence as one types their names.</p>
