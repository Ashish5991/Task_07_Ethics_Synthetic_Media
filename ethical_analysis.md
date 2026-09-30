# Phase A: Ethical Analysis of Synthetic Representation

## Starting From the Artifact

For Task 6, I created two short synthetic audio narrations from a verified analytical script. Both used Windows System.Speech text-to-speech, one with Microsoft David Desktop and one with Microsoft Zira Desktop. The files were labeled as AI-generated, opened with a spoken disclosure, and did not imitate an identifiable person. The content concerned the reliability of large-language-model analysis and was checked against independently generated results.

That project was low risk by design. The narration was truthful, the voice was generic, and the artifact was documented. Still, the work changed how I understand synthetic representation. A voice does more than transmit words. It suggests a speaker, a degree of preparation, and an institutional setting. Hearing the same verified analysis in a fluent voice made it feel more finished and authoritative than reading it as a markdown file, even though the audio added no evidence. The artifact also showed how little effort is required to separate a message from a person who can answer for it. A short script, a local tool, and a few minutes of editing were enough to make a shareable recording.

The Task 6 process also revealed an important limit to technical confidence. The exported WAV files had no C2PA content credentials or embedded disclosure metadata. Clear filenames and repository documentation were useful, but they would not reliably travel with a copied clip. This does not make labeling pointless. It means labeling is a practice that has to be repeated at points of distribution rather than treated as a permanent property of a file.

## Reasoning Across the Axes

### Truth: A fabricated emergency message

Imagine that the same text-to-speech workflow is used to create an audio message in which a university dean announces that a campus water supply is contaminated and that students must leave their residence halls immediately. The clip uses a generic but confident voice, includes the university name, and is posted to a student group shortly before an exam period. The creator does not need to imitate the dean perfectly. The urgency, the institutional vocabulary, and the familiar distribution channel may be enough to prompt action before listeners check the official website.

The ethical change is not only that the words are false. The synthetic delivery makes the claim easier to package as an official-sounding announcement and easier to circulate in a form that audiences treat as evidence. A written rumor can be read as a rumor; an audio announcement can be heard as proof that someone in authority spoke. The harm includes panic, disrupted emergency response, and a long-term loss of confidence in genuine emergency notices. The producer is responsible for the falsehood, but a platform and an institution also have responsibilities to make authentic channels easy to verify and to respond quickly when false material appears.

### Consent: A faculty member's voice used without permission

Imagine a student organization creates a polished synthetic audio message in the recognizable voice of a professor. The message asks students to support a particular campus referendum. Its content is not obviously false; the professor might personally agree with the position. However, the professor never authorized the use of their voice and learns about the recording only after students begin asking questions.

The central problem is not corrected by the apparent truthfulness of the message. The synthetic voice converts a person's identity and accumulated credibility into a tool for someone else's purpose. It removes the person's control over whether, when, and how they participate in a public controversy. It can also put the professor at risk of retaliation or make later authentic statements less believable. Consent is therefore not a one-time courtesy. It must be specific to the project, purpose, distribution channels, and timeframe, with a meaningful ability to revoke permission before publication.

### Context: A disclosure stripped from a legitimate clip

Imagine the communications office publishes a clearly labeled synthetic voiceover for an accessibility-oriented recap of a research event. The original post contains spoken disclosure, on-screen text, and a caption explaining that the narration is synthetic. A third party downloads ten seconds of the clip, removes the opening disclosure, and reposts the excerpt with a caption claiming that a researcher made the statement in an interview.

Here, the original producer acted carefully, but the context shifted. Disclosure is valuable because it informs the first audience, yet it can be lost through clipping, re-encoding, and reposting. The example shows why disclosure alone cannot establish authenticity or protect a speaker from misattribution. Producers should minimize the chance of harm by placing concise disclosures at the beginning and in descriptions, retaining source files and publication records, and avoiding synthetic depictions of identifiable people where the anticipated benefit is modest. Platforms should preserve labels where they can, but an organization cannot assume that they will.

### Scale: Thousands of tailored messages

Imagine a contractor generates thousands of short audio messages tailored to prospective students by name, major, hometown, and scholarship interest. Every message uses a pleasant synthetic voice and resembles a one-to-one outreach call. The messages are technically disclosed in a linked privacy notice, but listeners hear only a personalized invitation.

Scale changes the ethical stakes even if no individual message contains a direct lie. Automated personalization can make institutional outreach feel like individual attention that was never provided. It can pressure recipients, obscure who is responsible for the message, and make consent or complaint handling difficult. At scale, small design choices become a pattern of representation. The organization needs purpose limits, approval before automation, records of audience segments and templates, frequency controls, accessible opt-out mechanisms, and a human contact who can explain the message. Efficiency is not enough to justify impersonating a relationship.

## Mitigation Landscape

No mitigation below is a complete solution. Responsible governance requires layers of safeguards and a willingness to decline some uses.

### Disclosure

Spoken notices, visible labels, captions, and filenames can give the immediate audience relevant context. In Task 6, a spoken statement that the audio was synthetic and an `ai_generated` filename made the artifact's origin clear to someone receiving it in the repository. Disclosure works best when it is prominent, plain-language, and repeated in the caption or adjacent text.

It fails when audiences do not watch or listen from the beginning, when clips are excerpted, when labels are too vague, or when a repost drops the original caption. It also cannot repair a use that should never have been made, such as a nonconsensual imitation. Disclosure is necessary for many permitted uses, not a substitute for consent or review.

### Provenance and Content Credentials

Content credentials and cryptographic provenance systems, including the C2PA technical standard, can record assertions about where and how a file was created or edited. They promise a more inspectable chain of custody than a filename or a platform caption. A publisher can use them to help audiences and downstream services distinguish an original file from an unauthenticated copy.

The Task 6 WAV files did not contain C2PA credentials or embedded disclosure metadata. More generally, provenance can be absent at creation, stripped through conversion, unavailable in a receiving application, or misunderstood by viewers. A missing credential does not prove deception, and a credential does not prove that the underlying message is ethical or true. Provenance should be preserved when available and paired with publication records, rather than presented as proof of trustworthiness.

### Detection

Automated detection and forensic review can identify artifacts that may have been generated or manipulated. These methods are useful for triage, incident investigation, and assigning work for human review. They can raise the cost of casual deception and help an organization respond to suspected misuse.

Detection is not a reliable authenticity test. Models change, audio can be re-recorded or compressed, and detection systems can produce both false positives and false negatives. The absence of a detector flag cannot establish that a clip is genuine. Task 6's provenance check did not detect embedded credentials, but that result said nothing by itself about whether the audio was synthetic; the process log and source files were the meaningful evidence. Detection should trigger verification through official channels, not a public accusation.

### Law, Platforms, and Professional Norms

Legal approaches commonly address nonconsensual intimate imagery, election-related deception, false endorsement, privacy, consumer deception, and disclosure requirements. Platform policies may require labels, prohibit harmful impersonation, or provide reporting tools. Professional norms in journalism, advertising, education, and public relations can set higher expectations than the legal minimum, especially around transparency and consent.

These safeguards have uneven coverage. Laws differ by jurisdiction and may lag behind new tools. Platforms face enforcement delays and cannot reliably evaluate context at scale. Professional norms have limited force against actors outside the profession. An organization should comply with applicable law and platform rules, but its own policy must be clearer and stricter where institutional trust, safety, and consent demand it.

## Ethical Position

Synthetic media should be judged by more than whether it is technically impressive or accompanied by a label. The relevant questions are: What claim of identity or authority does it make? Whose voice or likeness is involved? What context may be lost when it is shared? What harm follows if the audience mistakes it for authentic speech? And is the benefit substantial enough to justify the residual risk?

The Task 6 artifact was appropriate because it used a generic voice, verified content, clear disclosure, and a limited research setting. Those conditions should not become a blanket permission. The same capability becomes materially more dangerous when it introduces false claims, uses a real person's identity without meaningful consent, detaches from disclosure, or scales personalized institutional messaging beyond human oversight.

## References and Further Reading

- Coalition for Content Provenance and Authenticity. [C2PA Specification](https://c2pa.org/specifications/).
- National Institute of Standards and Technology. [AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework).
- Federal Trade Commission. [Impersonation Rule](https://www.ftc.gov/business-guidance/resources/governments-businesses-impersonation-rule).
- [Task 6 synthetic-media project](../Task_06_Deep_Fake/).
