---
title: Say Command
toc:
- Voices: voices
- Commands: commands
---

The !say command allows you to send a text-to-speech message to be displayed on screen. The engine supports a few voices and has a few commands that can manipulate the appearance of the text on screen as well as how it sounds.

## Voices ##

To change your voice, use the `[voice <voice>]` command.

### appr-high ###

My voice (and the default voice), pitched to mimic the voices from Animal Crossing. It pronounces your text phoneme-by-phoneme.

### apprehentice ###

My voice, unpitched. This is useful for applying your own pitch modifications. It pronounces your text phoneme-by-phoneme.

### appr-low ###

My voice, pitched down to mimic cranky villagers from Animal Crossing. It pronounces your text phoneme-by-phoneme.

### bebebese ###

A soft popping sound that plays for every letter. Useful for adding a little character in the middle of other voices.

### silence ###

No sound

### vox ###

The Black Mesa Research Facility Automatic Diagnostic and Announcement System. This voice pronounces your text word-by-word.

Visit [https://half-life-vox.com/](https://half-life-vox.com/) to test out a sentence before sending it to !say, but remember to remove underscores before sending it.

### scratch ###

Record scratches, similar to the voices in the Katamari series. This voice speaks continuously until it runs out of text.

### sounds ###

Uses keywords to embed sounds into the phrase. Text in this voice will not be displayed on screen.

Available sounds are:

| Sound Name | Preview |
| -----------|------------------------------------------------------------ |
| bewoowoowoo | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/bewoowoowoo.wav" controls></audio> |
| clothflap | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/clothflap.wav" controls></audio> |
| explosion | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/explosion.wav" controls></audio> |
| fart1 | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/fart1.wav" controls></audio> |
| fart10 | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/fart10.wav" controls></audio> |
| fart11 | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/fart11.wav" controls></audio> |
| fart2 | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/fart2.wav" controls></audio> |
| fart3 | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/fart3.wav" controls></audio> |
| fart4 | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/fart4.wav" controls></audio> |
| fart5 | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/fart5.wav" controls></audio> |
| fart6 | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/fart6.wav" controls></audio> |
| fart7 | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/fart7.wav" controls></audio> |
| fart8 | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/fart8.wav" controls></audio> |
| fart9 | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/fart9.wav" controls></audio> |
| headknock | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/headknock.wav" controls></audio> |
| meow1 | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/meow1.wav" controls></audio> |
| meow2 | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/meow2.wav" controls></audio> |
| meow3 | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/meow3.wav" controls></audio> |
| meow4 | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/meow4.wav" controls></audio> |
| oof | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/oof.wav" controls></audio> |
| quack | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/quack.wav" controls></audio> |
| sirenwhistle | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/sirenwhistle.wav" controls></audio> |
| smallfart1 | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/smallfart1.wav" controls></audio> |
| smallfart10 | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/smallfart10.wav" controls></audio> |
| smallfart11 | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/smallfart11.wav" controls></audio> |
| smallfart12 | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/smallfart12.wav" controls></audio> |
| smallfart13 | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/smallfart13.wav" controls></audio> |
| smallfart2 | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/smallfart2.wav" controls></audio> |
| smallfart3 | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/smallfart3.wav" controls></audio> |
| smallfart4 | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/smallfart4.wav" controls></audio> |
| smallfart5 | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/smallfart5.wav" controls></audio> |
| smallfart6 | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/smallfart6.wav" controls></audio> |
| smallfart7 | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/smallfart7.wav" controls></audio> |
| smallfart8 | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/smallfart8.wav" controls></audio> |
| smallfart9 | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/smallfart9.wav" controls></audio> |
| toilet | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/toilet.wav" controls></audio> |
| trumpet | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/trumpet.wav" controls></audio> |
| whistledown | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/whistledown.wav" controls></audio> |
| whistleup | <audio src="https://files.clubvt.xyz/public/slickvegas/say/sounds/whistleup.wav" controls></audio> |

## Commands ##

Commands are executed by wrapping the command and its parameters in square brackets (Ex. `[command param1 param2 ... paramN]`.) Slick will attempt to validate commands before they're processed, but there's a chance it could fail to get to the overlay. If something doesn't work, check your commands and try again.

### Color ###

**Usage**: [color &lt;red&gt; &lt;green&gt; &lt;blue&gt;]

Sets the text color. Values are 0-255.

### Opacity ###

**Usage**: [opacity &lt;value&gt;]

Sets the text opacity. The value is 0-1.

### Stroke ###

**Usage**: [stroke &lt;red&gt; &lt;green&gt; &lt;blue&gt;]

Sets the text stroke color. Values are 0-255.

Use `[stroke off]` to reset.

### Size ###

**Usage**: [size &lt;value&gt;]

Sets the text size. Possible values are:

* littlest
* smallest
* tiniest
* tiny
* little
* small
* normal
* medium
* middle
* default
* big
* large
* xx-large
* biggest
* largest
* xxx-large

Use `[size off]` or `[size default]` to reset.

### Rainbow ###

**Usage**: [rainbow]

Toggles hue shift for the text.

### Wave ###

**Usage**: [wave]

Toggles the wave effect for the text.

### Shake ###

**Usage**: [shake]

Toggles the shake effect for the text.

### Dancing ###

**Usage**: [dancing]

Toggles dancing letters

<div title="Apprehentice is a genius — Abraham Lincoln, probably" style="display: flex;flex-direction: row; justify-content: space-around; width: 100%; margin: 0; padding: 0;">
<blockquote>
That's amusing, but also impossible to read<br />
— TASAgent
</blockquote>

<blockquote>
This pleases me, it is money well spent<br />
— HechoInMexico
</blockquote>


<blockquote>
Esto me complace, fue dinero bien gastado<br />
— ProductoDeMexico
</blockquote>

<blockquote>
Why are you asking me about this?<br />
— PrototypeFate
</blockquote>
</div>

### Grow ###

Toggles the grow effect. Text and images will start small, shrink out, and then grow back in, creating a sort of bouncing wave effect as they appear.

### Rate ###

**Usage**: [rate &lt;value&gt;]

Sets the rate at which the text is read. This affects pitch. Possible values range from 0.25-3.

### Pitch ###

**Usage**: [pitch &lt;value&gt;]

Sets the pitch at which the text is read. Possible values range from 0.25-3.

### Tempo ###

**Usage**: [tempo &lt;value&gt;]

Sets the tempo at which the text is read. This does not affect pitch. Possible values range from 0.25-3.

### Voice ###

**Usage**: [voice &lt;voice&gt;]

Sets the voice for the text after the command.

### Volume ###

**Usage**: [volume &lt;value&gt;]

Sets the volume for the voice. Possible values are 0-1. Default volume is 0.5.

### Filter ###

**Usage**: [filter &lt;filter&gt;]

Toggles the specified audio filter. There are currently no available filters.

### Pause ###

**Usage**: [pause &lt;time&gt;], [silence &lt;time&gt;]

Pauses for the specified time in milliseconds.

### Sine ###

**Usage**: [sine &lt;frequency&gt; &lt;time&gt; [text]]

Generates a sine tone with the specified frequency for the specified duration, displaying the specified text in its place. __I will revoke your permissions if you abuse this.__

### Triangle ###

**Usage**: [triangle &lt;frequency&gt; &lt;time&gt; [text]]

Generates a triangle tone with the specified frequency for the specified duration, displaying the specified text in its place. __I will revoke your permissions if you abuse this.__

### Sawtooth ###

**Usage**: [sawtooth &lt;frequency&gt; &lt;time&gt; [text]]

Generates a sawtooth tone with the specified frequency for the specified duration, displaying the specified text in its place. __I will revoke your permissions if you abuse this.__

### Square ###

**Usage**: [square &lt;frequency&gt; &lt;time&gt; [text]]

Generates a square tone with the specified frequency for the specified duration, displaying the specified text in its place. __I will revoke your permissions if you abuse this.__

### Noise ###

**Usage**: [noise &lt;frequency&gt; &lt;time&gt; [text]]

Generates a white noise with the specified frequency for the specified duration, displaying the specified text in its place. __I will revoke your permissions if you abuse this.__