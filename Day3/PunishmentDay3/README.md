1. HTML vs HTML5 (5 Differences)
Doctype Declaration: HTML uses complex DOCTYPEs (e.g., <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN">), while HTML5 simplifies it to <!DOCTYPE html>.
New Elements: HTML5 introduces semantic elements like <header>, <footer>, <article>, and <section>, absent in HTML.
Multimedia Support: HTML5 has native <audio> and <video> tags, reducing plugin dependency (e.g., Flash), unlike HTML.
Canvas and SVG: HTML5 supports <canvas> for dynamic graphics and better SVG integration; HTML lacks these.
APIs and Features: HTML5 includes APIs (e.g., Geolocation, Web Storage); HTML has limited scripting capabilities.

2. <b> vs <strong> (5 Differences)
Purpose: <b> is for visual bolding without semantic meaning; <strong> indicates important content with semantic emphasis.
Accessibility: Screen readers prioritize <strong> for emphasis; <b> is treated as stylistic.
SEO Impact: Search engines give <strong> more weight for content relevance; <b> is ignored.
HTML5 Semantics: <strong> is preferred in HTML5 for meaningful markup; <b> is presentational and less encouraged.
Default Styling: Both render text bold by default, but <b> can be restyled without semantic loss, unlike <strong>.

3. <em> vs <i> (Basic Syntax & 5 Differences)
Basic Syntax:

<em>: <em>Text</em> – Emphasizes text, typically italicized.
<i>: <i>Text</i> – Italicizes text for stylistic purposes.
Differences:

Semantics: <em> conveys importance or stress; <i> is purely presentational.
Accessibility: Screen readers may alter tone for <em>; <i> is ignored semantically.
SEO: <em> may influence search engine ranking; <i> has no SEO impact.
HTML5 Usage: <em> is semantic and preferred; <i> is for visual styling (e.g., icons, foreign words).
Default Rendering: Both often italicize, but <em>’s styling can be overridden while retaining meaning.

4. CSS vs CSS3 (5 Differences)
Version: CSS refers to earlier versions (CSS1, CSS2); CSS3 is the latest, modularized standard.
Features: CSS3 adds animations, transitions, and transforms; CSS lacks these.
Selectors: CSS3 introduces advanced selectors (e.g., :nth-child, [attr^=value]); CSS has basic selectors.
Layout: CSS3 supports Flexbox and Grid; CSS relies on floats and positioning.
Browser Support: CSS3 requires modern browsers for full features; CSS is universally supported.

5. HTML & CSS - Advantages and Disadvantages
HTML:

Advantages:
Structures web content effectively.
Easy to learn and implement.
Supported by all browsers.
Integrates with backend technologies.
Free and open standard.
Disadvantages:
Limited styling capabilities alone.
Static without scripting.
Inconsistent rendering across browsers.
Accessibility requires extra effort.
Large documents can be complex.
CSS:

Advantages:
Enhances visual presentation.
Separates style from content.
Reduces HTML code redundancy.
Supports responsive design.
Easy to maintain and update.
Disadvantages:
Browser compatibility issues.
Complex for advanced layouts.
Limited logic without preprocessors.
Performance impact with heavy styles.
Learning curve for animations/transitions.

6. HTML Video and Audio Tags (10 Examples)
Basic Video: <video src="video.mp4" controls>Your browser does not support video.</video>
Autoplay Video: <video src="video.mp4" autoplay controls>Your browser does not support video.</video>
Loop Video: <video src="video.mp4" loop controls>Your browser does not support video.</video>
Multi-Source Video: <video controls><source src="video.mp4" type="video/mp4"><source src="video.webm" type="video/webm">Your browser does not support video.</video>
Poster Video: <video src="video.mp4" poster="poster.jpg" controls>Your browser does not support video.</video>
Basic Audio: <audio src="audio.mp3" controls>Your browser does not support audio.</audio>
Autoplay Audio: <audio src="audio.mp3" autoplay controls>Your browser does not support audio.</audio>
Loop Audio: <audio src="audio.mp3" loop controls>Your browser does not support audio.</audio>
Multi-Source Audio: <audio controls><source src="audio.mp3" type="audio/mpeg"><source src="audio.ogg" type="audio/ogg">Your browser does not support audio.</audio>
Muted Video: <video src="video.mp4" muted controls>Your browser does not support video.</video>

