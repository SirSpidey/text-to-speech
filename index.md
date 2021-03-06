---

copyright:
  years: 2015, 2017
lastupdated: "2017-12-18"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:tip: .tip}
{:pre: .pre}
{:codeblock: .codeblock}
{:screen: .screen}
{:javascript: .ph data-hd-programlang='javascript'}
{:java: .ph data-hd-programlang='java'}
{:python: .ph data-hd-programlang='python'}
{:swift: .ph data-hd-programlang='swift'}

# About

> **Service update:** *The {{site.data.keyword.texttospeechshort}} service was updated on October 2, 2017. The service now lets you specify the endianness of audio that is returned in `audio/l16` format. For information about all recent changes to the service, see the [Release notes](/docs/services/text-to-speech/release-notes.html).*

The {{site.data.keyword.texttospeechfull}} service provides an Application Programming Interface (API) that uses {{site.data.keyword.IBM_notm}}'s speech-synthesis capabilities to convert written text to natural-sounding speech. The service streams the results back to the client with minimal delay. The service offers both [HTTP REST](/docs/services/text-to-speech/http.html) and [WebSocket](/docs/services/text-to-speech/websockets.html) interfaces.
{: shortdesc}

## Features and capabilities

The {{site.data.keyword.texttospeechshort}} service offers the following features and capabilities:

-   **Audio formats:** Produces audio in Ogg or WebM with the Opus or Vorbis codec, WAV, FLAC, MP3 (MPEG), l16 (PCM), mulaw, or basic format. See [Specifying an audio format](/docs/services/text-to-speech/http.html#format).
-   **Voices:** Synthesizes text to audio in a variety of languages, voices, and dialects. See [Specifying a voice](/docs/services/text-to-speech/http.html#voices).
-   **SSML:** Accepts plain text or text that is marked up with the XML-based Speech Synthesis Markup Language (SSML). See [Using SSML](/docs/services/text-to-speech/SSML.html).
-   **Expressiveness:** Extends SSML with an expressive element that lets you indicate a speaking style of *GoodNews*, *Apology*, or *Uncertainty*. Currently available only for the US English Allison voice. See [Expressive SSML](/docs/services/text-to-speech/SSML-expressive.html).
-   **Voice transformation:** Extends SSML by adding a voice transformation element that lets you expand the range of possible voices by controlling aspects such as pitch, rate, and timbre. Also offers two built-in virtual voices, *Young* and *Soft*. Currently available only for US English voices. See [Voice transformation SSML](/docs/services/text-to-speech/SSML-transform.html).
-   **Word timings:** With the WebSocket interface, supports the SSML `<mark>` element as well as optional word timing information for all strings of the input text. Timing information lets you synchronize the input text and the resulting audio. See [Obtaining word timings](/docs/services/text-to-speech/word-timing.html).
-   **Customization:** Provides a customization interface that lets you specify how the service pronounces unusual words that occur in your input. You can define pronunciations with the International Phonetic Alphabet (IPA) or {{site.data.keyword.IBM_notm}} Symbolic Phonetic Representation (SPR). See [Understanding customization](/docs/services/text-to-speech/custom-intro.html).

For information about the pricing plans available for the service, see the [{{site.data.keyword.texttospeechshort}} service in the {{site.data.keyword.Bluemix_short}} Catalog ![External link icon](../../icons/launch-glyph.svg "External link icon")](https://console.ng.bluemix.net/catalog/services/text-to-speech){: new_window}.

## Language support
{: #languages}

The service supports voices in the following languages: Brazilian Portuguese, English (UK and US dialects), French, German, Italian, Japanese, and Spanish (Castilian, Latin American, and North American dialects). The service offers at least one male or female voice, sometimes both, for each language. Each voice uses appropriate cadence and intonation for its dialect. For more information about the voices that are available for each language, see [Languages and voices](/docs/services/text-to-speech/http.html#languageVoices).

## Use cases
{: #usecases}

You can use the service in voice-driven and screenless interfaces, as well as in interfaces for the disabled. You can use the service in situations where audio is the preferred method of output, including home automation solutions, assistance tools for the vision-impaired, reading text and email messages aloud to drivers, video script narration and voice over, and reading-based educational tools.

## Try out the service

For examples of the service in action, see

-   A [quick demo ![External link icon](../../icons/launch-glyph.svg "External link icon")](https://text-to-speech-demo.ng.bluemix.net/){: new_window} of the {{site.data.keyword.texttospeechshort}} service that lets you enter text from which you can generate speech with different voices, including expressiveness and transformation where supported.
-   Applications in {{site.data.keyword.watson}} Developer Cloud [Starter Kits ![External link icon](../../icons/launch-glyph.svg "External link icon")](http://www.ibm.com/watson/developercloud/starter-kits.html){: new_window} that demonstrate the {{site.data.keyword.texttospeechshort}} service.
