<!--- I like <details> -->

# Polished Amethyst
A calm, deep purple theme for Discord forked from [the Amethyst Discord theme](https://github.com/spinfish/amethyst 'Thanks, Spinfish!').
This document contains original images from Spinfish for now till the theme is more updated.

![Main Preview](https://github.com/spinfish/images/blob/master/amethyst/preview_1.png)

## Installation
<details> <!-- -------------------------- detail -------------------------- -->
  <summary>Powercord</summary>
  <h4>To install Polished Amethyst with Powercord</h4>
  <ul>
    <li>Navigate to your <code>powercord</code> folder</li>
    <li>Go to <code>src > Powercord</code> and right click <code>themes</code></li>
    <li>Select <code>Git Bash here</code> (as shown below) and then type</li>
  </ul>
  <pre>git clone https://github.com/devchagrins/polished-amethyst</pre>
  <details>
    <summary>Screenshot of <code>Git Bash here</code></summary>
    <img src="https://media.discordapp.net/attachments/678012423067926539/835658793253470308/git_bash_here.png">
  </details>
</details>
<details> <!-- -------------------------- detail -------------------------- -->
  <summary>BetterDiscord</summary>
  <h4>To install Polished Amethyst with BetterDiscord</h4>
  <p>
    <h2>There is no published BetterDiscord theme! But this are directions for the original Amethyst.</h2>
    For a direct download, click <a href="https://betterdiscord.app/Download?id=422">here</a>. If you don't want that, do the following:
  </p>
  <ul>
    <li>Click <a href="https://betterdiscord.app/theme/Amethyst">here</a></li>
    <li>Press the big blue <code>Download</code> button</li>
    <li>Drag and drop the file into your <code>Themes</code> folder</li>
  </ul>
</details>

## Special features
<details> <!-- -------------------------- detail -------------------------- -->
  <summary>
    Polished Amethyst has a few special features up its sleeve for you to play around with! These are originally linked back to the Amethyst theme by Spinfish and all credit goes to him. These might see some updates as Polished Amethyst is updated.
  </summary>
  <ul>
    <li> <!-- -------------------------- li -------------------------- -->
      <h3>Custom-made addons</h3>
      <p>
        As of v1.0.0, Amethyst comes with custom-made addons which you can view in <a href="https://github.com/spinfish/amethyst/tree/master/extras">the extras folder</a>. To use one, simply paste the following CSS at the top of your Quick CSS file:
      </p>
      <pre><code>@import "https://spinfish.github.io/amethyst/extras/[ADDON-NAME-HERE].css";</code></pre>
      <details> <!-- -------------------------- detail -------------------------- -->
        <summary><code>settings-button</code> addon</summary>
        <img src="https://cdn.discordapp.com/attachments/666510091658330123/920872238759174174/amethyst-settings-button-addon.gif">
      </details>
      <details> <!-- -------------------------- detail -------------------------- -->
        <summary><code>custom-hljs-styling</code> addon</summary>
        <h3></h3>
        <p>
          As of v1.0.0, you can now customize Discord's codeblocks to your likings, Amethyst-style. Below are some pre-made colour schemes for you to enjoy. To use one, simply paste the code from your scheme of choice into your Quick CSS (make sure it's after the addon <code>@import</code>!).
        </p>
        <table>
          <tr>
            <th><img src="https://github.com/spinfish/images/blob/master/amethyst/hljs-scheme-1.png"></th>
            <th><img src="https://github.com/spinfish/images/blob/master/amethyst/hljs-scheme-2.png"></th>
            <th><img src="https://github.com/spinfish/images/blob/master/amethyst/hljs-scheme-3.png"></th>
            <th><img src="https://github.com/spinfish/images/blob/master/amethyst/hljs-scheme-4.png"></th>
          </tr>
          <tr>
            <td><pre><code>:root {
  --amethyst-hljs-1: rgb(95, 173, 212);
  --amethyst-hljs-2: rgb(141, 48, 108);
  --amethyst-hljs-3: rgb(112, 175, 178);
  --amethyst-hljs-4: rgb(115, 154, 102);
  --amethyst-hljs-5: rgb(148, 165, 187);
  --amethyst-hljs-6: rgb(147, 89, 163);
  --amethyst-hljs-7: rgb(126, 132, 199);
  --amethyst-hljs-8: rgb(122, 183, 161);
}</code></pre></td>
            <td><pre><code>:root {
  --amethyst-hljs-1: rgb(120, 101, 199);
  --amethyst-hljs-2: rgb(232, 146, 109);
  --amethyst-hljs-3: rgb(154, 180, 131);
  --amethyst-hljs-4: rgb(239, 222, 175);
  --amethyst-hljs-5: rgb(107, 217, 237);
  --amethyst-hljs-6: rgb(229, 145, 204);
  --amethyst-hljs-7: rgb(185, 144, 252);
  --amethyst-hljs-8: rgb(253, 186, 133);
}</code></pre></td>
            <td><pre><code>:root {
  --amethyst-hljs-1: rgb(187, 101, 179);
  --amethyst-hljs-2: rgb(241, 120, 107);
  --amethyst-hljs-3: rgb(81, 158, 127);
  --amethyst-hljs-4: rgb(199, 180, 119);
  --amethyst-hljs-5: rgb(45, 161, 191);
  --amethyst-hljs-6: rgb(148, 115, 178);
  --amethyst-hljs-7: rgb(112, 205, 202);
  --amethyst-hljs-8: rgb(171, 169, 118);
}</code></pre></td>
            <td><pre><code>:root {
  --amethyst-hljs-1: rgb(228, 211, 211);
  --amethyst-hljs-2: rgb(216, 113, 148);
  --amethyst-hljs-3: rgb(90, 241, 186);
  --amethyst-hljs-4: rgb(191, 172, 104);
  --amethyst-hljs-5: rgb(108, 118, 176);
  --amethyst-hljs-6: rgb(203, 145, 231);
  --amethyst-hljs-7: rgb(255, 112, 221);
  --amethyst-hljs-8: rgb(226, 226, 226);
}</code></pre></td>
          </tr>
        </table>
      </details>
    </li>
    <li> <!-- -------------------------- li -------------------------- -->
      <h3>Customizable margins and rounded corners</h3>
      <p>
        As of v1.0.0, you can now customize Amethyst's spacing and corner roundness properties! Simply head over to your Quick CSS, paste the following CSS into it, then adjust each of the `VALUE`s to your likings:
      </p>
      <pre><code>:root { <!-- I'm sorry you have to see this monstrosity -->
  --amethyst-margin: `VALUE`px; /* Default spacing: 4px */
  --amethyst-radius: `VALUE`px; /* Default roundness: 10px */
}</code></pre>
      <details>
        <summary>Here's what Polished Amethyst looks like with the margin property set to `8px` and the radius property to `0px`:</summary>
        <img src="https://github.com/spinfish/images/blob/master/amethyst/preview_margin_8px_radius_0px.png">
      </details>
    </li>
  </ul>
</details>

## Extra previews
<details>
  <summary>Home page</summary>
  <img src="https://github.com/spinfish/images/blob/master/amethyst/preview_2.png">
</details>
<details>
  <summary>User settings</summary>
  <img src="https://github.com/spinfish/images/blob/master/amethyst/preview_3.png">
</details>
<details>
  <summary>Open thread</summary>
  <img src="https://github.com/spinfish/images/blob/master/amethyst/preview_4.png">
</details>

## Acknowledgements
<details>
  <summary>Without these people this theme would never have been made 💙</summary>
  <br>

  Shout out to all these people, without whom, this theme would not exist at all.

  - **[Spinfish](https://github.com/Spinfish)** for the [Amethyst](https://github.com/spinfish/amethyst) theme which this was originally spun off of

</details>
