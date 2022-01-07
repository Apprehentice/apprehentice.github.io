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

Visit [https://half-life-vox.com/#vox_login](https://half-life-vox.com/#vox_login) to test out a sentence before sending it to !say, but remember to remove underscores before sending it.

### sounds ###

Uses keywords to embed sounds into the phrase. Text in this voice will not be displayed on screen.

Available sounds are:

* bewoowoowoo
* clothflap
* explosion
* fart1
* fart10
* fart11
* fart2
* fart3
* fart4
* fart5
* fart6
* fart7
* fart8
* fart9
* headknock
* meow1
* meow2
* meow3
* meow4
* oof
* quack
* sirenwhistle
* smallfart1
* smallfart10
* smallfart11
* smallfart12
* smallfart13
* smallfart2
* smallfart3
* smallfart4
* smallfart5
* smallfart6
* smallfart7
* smallfart8
* smallfart9
* toilet
* trumpet
* whistledown
* whisthleup

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