---
title: Best practices index
tags: [practices, index]
status: verified
updated: 2026-10-19
---

# Best practices

These pages are the stable interface and experience practices. Lessons in `Lessons-Learned/` are evidence from a real flow. When a lesson becomes a general rule, fold it into a page here and leave the lesson in place as the evidence.

The pages are platform-neutral. A design tool, a component library, or a frontend framework is named only on an official-documentation pointer, when a reader needs the current source.

| Guide | Use it when |
| --- | --- |
| [Consult before an interface decision](01-consult-before-an-interface-decision.md) | Starting a decision another screen will repeat |
| [Name the user, the task, and done](02-name-the-user-task-and-done.md) | Framing an interface task |
| [Compare interaction options](03-compare-interaction-options.md) | More than one pattern could complete the task |
| [Design states with the main path](04-design-states-with-the-main-path.md) | Specifying empty, loading, error, and success |
| [Meet accessibility expectations](05-meet-accessibility-expectations.md) | Checking keyboard use, labels, contrast, and non-color cues |
| [Test the flow and record](06-test-the-flow-and-record.md) | Finishing a flow or saving a lesson |
| [Separate practice from product](07-separate-practice-from-product.md) | Deciding whether a finding belongs here |
| [Write searchable pages](08-write-searchable-pages.md) | Adding a page a later search should find |
| [Structure information before navigation](09-structure-information-before-navigation.md) | Grouping tasks and objects before choosing navigation |
| [Set visual hierarchy by importance](10-set-visual-hierarchy-by-importance.md) | Deciding what a person sees first |
| [Name the outcome on the control](11-name-the-outcome-on-the-control.md) | Writing the words on a link or button |
| [Show where the person is and how to go back](12-show-where-the-person-is.md) | Marking the current place and the way out |
| [Let people control a time limit](13-let-people-control-a-time-limit.md) | A timer would expire the task |
| [Let people reduce motion](14-let-people-reduce-motion.md) | An interaction animates more than the task needs |
| [Size targets so the neighbor is safe](15-size-targets-so-the-neighbor-is-safe.md) | Controls are small or close together |
| [Expose the structure people can see](16-expose-the-structure-people-can-see.md) | Headings, groups, or tables carry a relationship |
| [Share a pattern when a second screen needs it](17-share-a-pattern-when-it-repeats.md) | Deciding whether an interaction becomes a shared rule |
| [Confirm only what is hard to undo](18-confirm-only-what-is-hard-to-undo.md) | An action can destroy work or cannot be undone |
| [Give meaningful images a text alternative](19-give-meaningful-images-a-text-alternative.md) | Use this when a non-text element is shown to the person |
| [Offer an alternative for audio or silent video](20-offer-an-alternative-for-audio-or-silent-video.md) | Use this when the recording is the information, not a labeled alternative to text already on the view |
| [Caption prerecorded speech](21-caption-prerecorded-speech.md) | Use this for recorded media. A clip that is a labeled alternative for text on the page is the exception named in the criterion |
| [Describe or replace prerecorded video](22-describe-or-replace-prerecorded-video.md) | Use this when the picture carries information the soundtrack does not |
| [Caption live speech](23-caption-live-speech.md) | Use this for a live stream, a live event, or any audio that is happening as the person watches |
| [Audio-describe prerecorded video](24-audio-describe-prerecorded-video.md) | Use this when you are meeting the stronger description requirement, not only offering a separate transcript |
| [Offer sign language for prerecorded audio](25-offer-sign-language-for-prerecorded-audio.md) | Use this when the product commits to the sign-language criterion, or when the audience depends on sign language |
| [Extend description when speech does not pause](26-extend-description-when-speech-does-not-pause.md) | Use this when audio description cannot fit in the natural gaps |
| [Provide a full text alternative for prerecorded media](27-provide-a-full-text-alternative-for-prerecorded-media.md) | Use this when a description track is not enough and the person needs the whole story in text |
| [Offer an alternative for live audio only](28-offer-an-alternative-for-live-audio-only.md) | Use this for a live audio broadcast, a voice-only event, or a live announcement |
| [Keep reading order meaningful](29-keep-reading-order-meaningful.md) | Use this when columns, cards, or positioned regions would be read in the wrong order if taken one after another |
| [Pair sensory instructions with text](30-pair-sensory-instructions-with-text.md) | Use this whenever help text tells the person what to press or where to look |
| [Let people choose orientation](31-let-people-choose-orientation.md) | Use this for views the person may rotate. A check deposit, a piano, a slide, or a virtual-reality view can be the essential exception. Confirm that exception |
| [Identify the purpose of common fields](32-identify-common-input-purpose.md) | Use this when the platform can express the purpose of a user field |
| [Let people stop autoplaying audio](33-let-people-stop-autoplaying-audio.md) | Use this when a view starts sound on its own |
| [Meet the text contrast minimum](34-meet-the-text-contrast-minimum.md) | Use this for text the person must read. Confirm the ratios on the current page before you treat a number as the rule |
| [Let people resize text](35-let-people-resize-text.md) | Use this for body text, labels, and instructions |
| [Use real text instead of a picture of text](36-use-real-text-instead-of-a-picture-of-text.md) | Use this for headings, buttons, and quotations that someone might otherwise export as an image |
| [Keep speech clear of background audio](37-keep-speech-clear-of-background-audio.md) | Use this for a spoken lesson, a story, or an announcement. Music, an audio logo, and an audio CAPTCHA are outside it |
| [Let people change text presentation](38-let-people-change-text-presentation.md) | Use this when you present paragraphs. Confirm the current measurements before you treat them as the only legal layout |
| [Reserve images of text for what must be drawn](39-reserve-images-of-text-for-what-must-be-drawn.md) | Use this when you are meeting that stronger criterion |
| [Reflow without two-way scrolling](40-reflow-without-two-way-scrolling.md) | Use this when a layout was designed wide and then zoomed or narrowed |
| [Meet non-text contrast](41-meet-non-text-contrast.md) | Use this for input borders, icons that mean something, and selected states. Inactive controls and untouched user-agent controls have the exceptions in the criterion |
| [Survive increased text spacing](42-survive-increased-text-spacing.md) | Use this for text in a markup language that allows those style overrides. The page does not have to use those values itself |
| [Keep hover and focus content usable](43-keep-hover-and-focus-content-usable.md) | Use this for a custom tooltip, a submenu, or any popup the product draws. A browser tooltip the product did not restyle is the user-agent exception |
| [Offer a keyboard way out](44-offer-a-keyboard-way-out.md) | Use this for a dialog, a custom widget, or any region that might hold focus. A layer that traps focus without an announced exit fails the task |
| [Let people turn off character shortcuts](45-let-people-turn-off-character-shortcuts.md) | Use this when the product defines single-character shortcuts |
| [Let people pause moving content](46-let-people-pause-moving-content.md) | Use this when the page starts the motion. Motion the person triggered is the reduced-motion rule |
| [Let people postpone interruptions](47-let-people-postpone-interruptions.md) | Use this when the stronger interruptions criterion is in scope, and whenever a notification can wait |
| [Preserve work after reauthentication](48-preserve-work-after-reauthentication.md) | Use this for a form, a draft, or any activity that outlasts the session |
| [Warn before inactivity deletes work](49-warn-before-inactivity-deletes-work.md) | Use this when a timeout clears a draft or a cart. Privacy rules may limit storing data before the person is known. Confirm that note |
| [Keep flashes at or below three a second](50-keep-flashes-at-or-below-three-a-second.md) | Use this for animation, video, and large transitions |
| [Offer a way past repeated blocks](51-offer-a-way-past-repeated-blocks.md) | Use this when the same large block precedes the task on many views |
| [Title the view by its purpose](52-title-the-view-by-its-purpose.md) | Use this for a page, a screen, or a document the person opens |
| [Make link purpose clear in context](53-make-link-purpose-clear-in-context.md) | Use this together with the rule that a control names its outcome. Context may help. It does not rescue a link whose text is only "click here" when the context is also vague |
| [Offer more than one way to find a view](54-offer-more-than-one-way-to-find-a-view.md) | Use this for a body of content, not for the second step of a checkout |
| [Keep focus from being fully hidden](55-keep-focus-from-being-fully-hidden.md) | Use this for sticky headers, banners, and layers. Content the person opened may cover focus if they can reveal the control without moving focus. Confirm that note |
| [Make the focus indicator meet the appearance minimum](56-make-the-focus-indicator-meet-the-appearance-minimum.md) | Use this when the product changes the focus style. An untouched user-agent indicator is the exception |
| [Offer a simple pointer alternative to a gesture](57-offer-a-simple-pointer-alternative-to-a-gesture.md) | Use this for pinch, multi-finger, or drag-a-path actions the product interprets |
| [Fire the action on release](58-fire-the-action-on-release.md) | Use this for buttons and other pointer targets |
| [Include the visible label in the name](59-include-the-visible-label-in-the-name.md) | Use this when speech control or a screen reader will activate the control by its visible words |
| [Let people turn off motion controls](60-let-people-turn-off-motion-controls.md) | Use this for shake, tilt, or raise-to-act. This is separate from decorative animation |
| [Give primary targets the larger size](61-give-primary-targets-the-larger-size.md) | Use this for primary actions. Inline text links, untouched user-agent controls, an equivalent larger control, and essential dense layouts have the exceptions in the criterion |
| [Allow the platform input methods](62-allow-the-platform-input-methods.md) | Use this when a view might block a keyboard, a pointer, or speech |
| [Offer a non-drag way to do the same thing](63-offer-a-non-drag-way-to-do-the-same-thing.md) | Use this for reorder, sliders the product scripts, and drag-and-drop. A native control the product did not restyle can be the user-agent exception |
| [Set the language of the view](64-set-the-language-of-the-view.md) | Use this on every view |
| [Mark a passage in another language](65-mark-a-passage-in-another-language.md) | Use this when a sentence switches language |
| [Define words used in a special way](66-define-words-used-in-a-special-way.md) | Use this when a term does not mean what the person would expect |
| [Expand abbreviations](67-expand-abbreviations.md) | Use this the first time an abbreviation carries meaning the person needs |
| [Offer a plainer version of difficult text](68-offer-a-plainer-version-of-difficult-text.md) | Use this for instructions the person must follow. Confirm the current education-level wording before you treat a grade number as the test |
| [Mark pronunciation when meaning depends on it](69-mark-pronunciation-when-meaning-depends-on-it.md) | Use this for the rare word that changes meaning with pronunciation, not for every name |
| [Leave the context alone when focus arrives](70-do-not-change-context-when-focus-arrives.md) | Use this for every focusable control |
| [Warn before input changes context](71-warn-before-input-changes-context.md) | Use this for a select, a radio group, or a toggle that might navigate or submit |
| [Keep repeated navigation in the same order](72-keep-repeated-navigation-in-the-same-order.md) | Use this for a global menu, a local section menu, or a footer that repeats |
| [Identify the same function the same way](73-identify-the-same-function-the-same-way.md) | Use this for search, save, next, and any repeated action |
| [Change context only on request](74-change-context-only-on-request.md) | Use this when you are meeting the stronger predictable-behavior criterion |
| [Put repeated help in the same order](75-put-repeated-help-in-the-same-order.md) | Use this when more than one view offers help |
| [Identify an input error in text](76-identify-an-input-error-in-text.md) | Use this at the field or the submission. A red border without text is not the description |
| [Label or instruct before input](77-label-or-instruct-before-input.md) | Use this for every field, including one that looks obvious to the team |
| [Suggest a correction when you know one](78-suggest-a-correction-when-you-know-one.md) | Use this for a format, a range, or a value the system can recognize |
| [Let people review a consequential submission](79-let-people-review-a-consequential-submission.md) | Use this before the person is committed. A delete confirmation is a related, narrower rule |
| [Offer help for the current step](80-offer-help-for-the-current-step.md) | Use this when you are meeting the stronger help criterion, and whenever a field's rule is easy to get wrong |
| [Let people check any submission](81-let-people-check-any-submission.md) | Use this when that criterion is in scope |
| [Do not ask for the same fact twice](82-do-not-ask-for-the-same-fact-twice.md) | Use this across steps of one process |
| [Let people authenticate without a puzzle](83-let-people-authenticate-without-a-puzzle.md) | Use this for passwords, codes, and CAPTCHA-like steps |
| [Avoid a memory test even as an alternative path](84-avoid-a-memory-test-even-as-an-alternative-path.md) | Use this when that stronger criterion is in scope |
| [Expose name, role, and value](85-expose-name-role-and-value.md) | Use this when you build a control instead of using a platform control that already exposes them |
| [Announce status without stealing focus](86-announce-status-without-stealing-focus.md) | Use this for a confirmation, a search-result count, or a progress update that appears away from the focused control |
| [Expose the purpose of regions and icons](87-expose-the-purpose-of-regions-and-icons.md) | Use this when that criterion is in scope |
| [Keep every edge of focus visible](88-keep-every-edge-of-focus-visible.md) | Use this when that criterion is in scope. The minimum criterion only forbids hiding the control entirely |
| [Use headings to organize long text](89-use-headings-to-organize-long-text.md) | Use this for an article, a policy, or help text with more than one topic |
| [Avoid making time the point of the task](90-avoid-making-time-the-point-of-the-task.md) | Use this when you can remove a clock entirely |
| [Identify each link from its text alone](91-identify-each-link-from-its-text-alone.md) | Use this when you are meeting the stronger link criterion. The minimum criterion allows programmatic context |
| [Show options people can recognize](92-show-options-people-can-recognize.md) | Use this when the person must pick a function, a product they already saw, or a next step |
| [Teach with a tip on the step](93-teach-with-a-tip-on-the-step.md) | Use this the first time a gesture or a rare control appears |
| [Show the frequent options first](94-show-the-frequent-options-first.md) | Use this when a view has both everyday choices and specialist ones |
| [Keep a step to the choices used together](95-keep-a-step-to-the-choices-used-together.md) | Use this when one screen is either too crowded or split so the person cannot compare |
| [Write the error where it happened](96-write-the-error-where-it-happened.md) | Use this when the system rejects or cannot complete an input |
| [Match the warning to the severity](97-match-the-warning-to-the-severity.md) | Use this when you choose between an inline message and a dialog |
| [Interrupt with a modal only when the task requires it](98-interrupt-with-a-modal-only-when-the-task-requires-it.md) | Use this when something might cover the view and demand an answer |
| [Use the person's words](99-use-the-persons-words.md) | Use this for labels, navigation, and errors |
| [Leave out what the task does not need](100-leave-out-what-the-task-does-not-need.md) | Use this when a view has accumulated asides, promotions, or repeated explanations |
| [Offer a faster path without hiding the basic one](101-offer-a-faster-path-without-hiding-the-basic-one.md) | Use this for a repeated command |
| [Make help searchable and about the task](102-make-help-searchable-and-about-the-task.md) | Use this when the task needs an explanation that will not fit on the control |
| [Prevent slips with a constraint or a safe default](103-prevent-slips-with-a-constraint-or-a-safe-default.md) | Use this before you add another confirmation |
| [Report status in time for the next step](104-report-status-in-time-for-the-next-step.md) | Use this for save, send, submit, and any action whose result is not obvious on the same control |
| [Use the same words for the same situation](105-use-the-same-words-for-the-same-situation.md) | Use this across views in one product. Platform conventions still apply; confirm the current platform page before you invent a local name for a standard action |
| [Suggest the fix instead of only naming the fault](106-suggest-the-fix-instead-of-only-naming-the-fault.md) | Use this for a mismatch the system can resolve, such as a city that does not match a code |
| [Meet the stronger text contrast](107-meet-the-stronger-text-contrast.md) | Use this when you are aiming past the minimum text contrast. Confirm both ratios before you treat them as the rule |
| [Do not flash above three times a second](108-do-not-flash-above-three-times-a-second.md) | Use this when that stronger criterion is in scope |
| [Operate every function from the keyboard](109-operate-every-function-from-the-keyboard.md) | Use this when that criterion is in scope. The general keyboard expectation still applies when it is not |
| [Provide a visible keyboard focus mode](110-provide-a-visible-keyboard-focus-mode.md) | Use this even when a pointer mode draws no extra indicator. The size and contrast of a custom indicator are a separate rule |
| [Show recent work so the person can resume](111-show-recent-work-so-the-person-can-resume.md) | Use this when a task is often interrupted and continued later |
| [Offer suggestions so a query can be recognized](112-offer-suggestions-so-a-query-can-be-recognized.md) | Use this for search and for any field whose valid values are a set the system knows |
| [Let a noncritical message stay out of the way](113-let-a-noncritical-message-stay-out-of-the-way.md) | Use this for a status, a hint, or a notice that can wait |
| [Tell the person before a consequential action](114-tell-the-person-before-a-consequential-action.md) | Use this for save, send, pay, delete, and any change they cannot see on the control itself |
| [Match the control to the expected outcome](115-match-the-control-to-the-expected-outcome.md) | Use this when several controls affect several objects, such as a set of options in a row |
| [Prevent the costly error first](116-prevent-the-costly-error-first.md) | Use this when you rank which mistakes to design out |
| [Let people tailor a frequent action](117-let-people-tailor-a-frequent-action.md) | Use this for a frequent view, filter, or command |
| [Keep needed information on the step](118-keep-needed-information-on-the-step.md) | Use this when a later step depends on an earlier choice, a code, or a price |
| [Hide a decorative image from the name](119-hide-a-decorative-image-from-the-name.md) | Use this when a picture is a border, a spacer, or an illustration of text already beside it. |
| [Name a functional image by its action](120-name-a-functional-image-by-its-action.md) | Use this when an icon, a logo, or a picture is the control. |
| [Give a complex image a long description](121-give-a-complex-image-a-long-description.md) | Use this when the picture holds more than one sentence of information. |
| [Name a group of images once](122-name-a-group-of-images-once.md) | Use this for a rating, a score, or any row of pictures that together mean one thing. |
| [Describe each image in a collection](123-describe-each-image-in-a-collection.md) | Use this when each image is its own information, not a fragment of one fact. |
| [Name each region of an image map](124-name-each-region-of-an-image-map.md) | Use this when one picture contains more than one link. |
| [Repeat the words shown in an image of text](125-repeat-the-words-shown-in-an-image-of-text.md) | Use this when a logo or a picture must keep lettering that real text cannot replace. |
| [Keep images that carry the interface](126-keep-images-that-carry-the-interface.md) | Use this when someone proposes a separate text-only version of a view. |
| [Do not repeat adjacent text in the alternative](127-do-not-repeat-adjacent-text-in-the-alternative.md) | Use this when a caption or a paragraph fully describes the picture. |
| [Name an icon that changes the destination](128-name-an-icon-that-changes-the-destination.md) | Use this when a small picture sits in a link and changes what the person should expect. |
| [Do not use color as the only cue](129-do-not-use-color-as-the-only-cue.md) | Use this when color marks a required field, an error, a status, a series, or a link. |
| [Describe the topic in the heading or label](130-describe-the-topic-in-the-heading-or-label.md) | Use this whenever a heading or a label is shown. |
| [Do not skip heading ranks](131-do-not-skip-heading-ranks.md) | Use this when a view has more than one level of heading. |
| [Keep heading ranks stable in repeated regions](132-keep-heading-ranks-stable-in-repeated-regions.md) | Use this when a region repeats beside content whose headings change. |
| [Mark the regions of the view](133-mark-the-regions-of-the-view.md) | Use this on a view that has more than one block of content. |
| [Label regions that share a type](134-label-regions-that-share-a-type.md) | Use this when a view has two navigation blocks, or any repeated region type. |
| [Give a data table a caption](135-give-a-data-table-a-caption.md) | Use this when a grid of related values is shown. |
| [Summarize a complex table without repeating the caption](136-summarize-a-complex-table-without-repeating-the-caption.md) | Use this when row and column structure is unusual enough that a person needs a map. |
| [Do not use a table to lay out the view](137-do-not-use-a-table-to-lay-out-the-view.md) | Use this when you are tempted to place headings, images, or fields into table cells for alignment. |
| [Associate every data cell with its headers](138-associate-every-data-cell-with-its-headers.md) | Use this for any grid a person reads one cell at a time. |
| [Make each label clear without the group name](139-make-each-label-clear-without-the-group-name.md) | Use this when several fields share a group label, such as two addresses. |
| [Name a set of radio options as a group](140-name-a-set-of-radio-options-as-a-group.md) | Use this whenever the person picks one of several radios. |
| [Keep the group name short](141-keep-the-group-name-short.md) | Use this when related fields or options share one legend. |
| [Group options in a long list](142-group-options-in-a-long-list.md) | Use this when a single list mixes several categories. |
| [Ask only for what the task needs](143-ask-only-for-what-the-task-needs.md) | Use this when you add a field. |
| [Put the form instructions before the fields](144-put-the-form-instructions-before-the-fields.md) | Use this for required markers, shared formats, and where to find help. |
| [Put the expected format in the label](145-put-the-expected-format-in-the-label.md) | Use this for a date, a code, or any field with a required pattern. |
| [Keep a visible label on every field](146-keep-a-visible-label-on-every-field.md) | Use this for text fields, choices, and lists. |
| [Let the label activate the control](147-let-the-label-activate-the-control.md) | Use this for radios, checkboxes, and any small control. |
| [Place the label with its field](148-place-the-label-with-its-field.md) | Use this for every field. |
| [Associate the label with that field](149-associate-the-label-with-that-field.md) | Use this for every field you label. |
| [Do not use a tooltip as the name](150-do-not-use-a-tooltip-as-the-name.md) | Use this when a field has no visible label and someone suggests a title or a hover tip. |
| [Keep a hidden name available](151-keep-a-hidden-name-available.md) | Use this only when the visible context already identifies the field, such as a search field beside a Search button. |
| [Do not remove a name from everyone](152-do-not-remove-a-name-from-everyone.md) | Use this when you visually hide a label or a hint. |
| [Split a long form into logical steps](153-split-a-long-form-into-logical-steps.md) | Use this when one form is long enough to discourage people. |
| [Repeat shared instructions on every step](154-repeat-shared-instructions-on-every-step.md) | Use this when a form spans more than one view. |
| [Let people skip an optional stage](155-let-people-skip-an-optional-stage.md) | Use this when a step does not apply to everyone. |
| [Say how many steps will follow](156-say-how-many-steps-will-follow.md) | Use this for a process with a known sequence. |
| [Put the step count first in the title](157-put-the-step-count-first-in-the-title.md) | Use this when a process is a series of views. |
| [Name the step in the main heading](158-name-the-step-in-the-main-heading.md) | Use this on every step of a multi-step form. |
| [Mark completed and current steps in text](159-mark-completed-and-current-steps-in-text.md) | Use this when a known number of steps is shown as a sequence. |
| [Let people reopen a completed step](160-let-people-reopen-a-completed-step.md) | Use this when a step indicator lists earlier steps. |
| [Report whether the submission worked](161-report-whether-the-submission-worked.md) | Use this when the person sends a form. |
| [List the errors before the fields](162-list-the-errors-before-the-fields.md) | Use this after a submission with more than one error. |
| [Name the field in the error](163-name-the-field-in-the-error.md) | Use this in a summary and beside the field. |
| [Move focus to the first error](164-move-focus-to-the-first-error.md) | Use this when the person submits and the view stays put. |
| [Wait to flag a format until the field is finished](165-wait-to-flag-a-format-until-the-field-is-finished.md) | Use this for a date, a code, or any value that is incomplete while they type. |
| [Announce typing feedback politely](166-announce-typing-feedback-politely.md) | Use this for a live check, such as whether a name is available. |
| [Announce a format error when the field is left](167-announce-a-format-error-when-the-field-is-left.md) | Use this when the check runs on leaving the field. |
| [Put the outcome first in the title](168-put-the-outcome-first-in-the-title.md) | Use this when a submission reloads the view or replaces it. |
| [Pair a valid or invalid cue with text](169-pair-a-valid-or-invalid-cue-with-text.md) | Use this for inline success and error on a field. |
| [Use one column for a form](170-use-one-column-for-a-form.md) | Use this for a form longer than a couple of fields. |
| [Follow a familiar field order](171-follow-a-familiar-field-order.md) | Use this when a form asks for a known sequence, such as a payment or a shipment. |
| [Show a short set of options](172-show-a-short-set-of-options.md) | Use this when the person is choosing among a very small set. |
| [Size the field to the answer](173-size-the-field-to-the-answer.md) | Use this when you set the width of a field. |
| [Label the optional fields](174-label-the-optional-fields.md) | Use this when a form includes a question some people may skip. |
| [State the format before the person fails](175-state-the-format-before-the-person-fails.md) | Use this for passwords, phone numbers, and any field with a syntax. |
| [Do not offer a control that clears the form](176-do-not-offer-a-control-that-clears-the-form.md) | Use this at the end of a form. |
| [Make cancel quieter than submit](177-make-cancel-quieter-than-submit.md) | Use this when a form collects sensitive input and people need a way to discard it. |
| [Make an error unmistakable](178-make-an-error-unmistakable.md) | Use this when a field fails validation. |
| [Show one tab panel at a time](179-show-one-tab-panel-at-a-time.md) | Use this when related content splits into a few peer groups. |
| [Keep every tab in view](180-keep-every-tab-in-view.md) | Use this when you add another tab. |
| [Keep critical content on the selected tab](181-keep-critical-content-on-the-selected-tab.md) | Use this when one tab is shown by default. |
| [Do not split a comparison across tabs](182-do-not-split-a-comparison-across-tabs.md) | Use this when two panels would have to be remembered to be compared. |
| [Do not mix navigation tabs with in-page tabs](183-do-not-mix-navigation-tabs-with-in-page-tabs.md) | Use this when several tabs share one list. |
| [Mark the selected tab in more than one way](184-mark-the-selected-tab-in-more-than-one-way.md) | Use this for every tab list, and especially when there are only two tabs. |
| [Keep unselected tabs readable](185-keep-unselected-tabs-readable.md) | Use this for every tab that is not selected. |
| [Keep the selected tab next to its panel](186-keep-the-selected-tab-next-to-its-panel.md) | Use this when you place a tab list and its panel. |
| [Use a single row of tabs](187-use-a-single-row-of-tabs.md) | Use this for a website or a simple app. |
| [Put the tab list before the panel](188-put-the-tab-list-before-the-panel.md) | Use this for in-page tabs. |
| [Select the frequent tab by default](189-select-the-frequent-tab-by-default.md) | Use this when you choose the default tab. |
| [Write a short tab label](190-write-a-short-tab-label.md) | Use this when you name a tab. |
| [Reserve endless scroll for open browsing](191-reserve-endless-scroll-for-open-browsing.md) | Use this when you choose how a long list grows. |
| [Return the person to their place in the list](192-return-the-person-to-their-place-in-the-list.md) | Use this when a list opens a detail and the person goes back. |
| [Show that more items are loading](193-show-that-more-items-are-loading.md) | Use this when a list fetches more as the person reaches the bottom. |
| [Let people reach the end of the view](194-let-people-reach-the-end-of-the-view.md) | Use this when content keeps loading as the person scrolls. |
| [Show the hierarchy in the breadcrumb](195-show-the-hierarchy-in-the-breadcrumb.md) | Use this on a deep view that has real ancestors. |
| [Keep breadcrumbs secondary to navigation](196-keep-breadcrumbs-secondary-to-navigation.md) | Use this when you add a breadcrumb trail. |
| [Show one parent path](197-show-one-parent-path.md) | Use this in a structure where a page can live in several places. |
| [Do not link the current crumb](198-do-not-link-the-current-crumb.md) | Use this at the end of a breadcrumb trail. |
| [Include only real pages in the trail](199-include-only-real-pages-in-the-trail.md) | Use this when a menu has labels that are not destinations. |
| [Do not wrap the breadcrumb trail](200-do-not-wrap-the-breadcrumb-trail.md) | Use this when a trail is shown on a narrow view. |
| [Label an icon with visible text](201-label-an-icon-with-visible-text.md) | Use this for navigation and for any icon that is not a truly standard action. |
| [Do not invent an icon for an abstract idea](202-do-not-invent-an-icon-for-an-abstract-idea.md) | Use this when a navigation item or an action has no familiar symbol. |
| [Represent a menu as a list](203-represent-a-menu-as-a-list.md) | Use this for navigation and for a sequence of steps presented as a menu. |
| [Label every menu on the view](204-label-every-menu-on-the-view.md) | Use this when a view has one or more menus. |
| [Mark the current item in the menu](205-mark-the-current-item-in-the-menu.md) | Use this for the item that matches the open view. |
| [Expose the current page in the menu](206-expose-the-current-page-in-the-menu.md) | Use this when the current item stays in the tab order. |
| [Keep the same menu order at every size](207-keep-the-same-menu-order-at-every-size.md) | Use this when a menu collapses on a small view. |
| [Offer another way out of a flyout](208-offer-another-way-out-of-a-flyout.md) | Use this when a menu reveals a submenu on hover or on a pointer move. |
| [Show whether a submenu is open](209-show-whether-a-submenu-is-open.md) | Use this for a drop-down or fly-out in navigation. |
| [Do not open a submenu on tab](210-do-not-open-a-submenu-on-tab.md) | Use this for a menu with submenus. |
| [Delay closing a flyout](211-delay-closing-a-flyout.md) | Use this when a submenu opens from a pointer hover. |
| [Separate a parent link from its submenu control](212-separate-a-parent-link-from-its-submenu-control.md) | Use this when the parent is both a destination and the owner of children. |
| [Name the parent in the submenu control](213-name-the-parent-in-the-submenu-control.md) | Use this when a button shows or hides children. |
| [Let people pause a carousel](214-let-people-pause-a-carousel.md) | Use this when slides advance without a request. |
| [Announce the carousel item that is showing](215-announce-the-carousel-item-that-is-showing.md) | Use this whenever a carousel moves to another item. |
| [Do not steal focus when a carousel moves](216-do-not-steal-focus-when-a-carousel-moves.md) | Use this for a carousel with automatic motion or with previous and next controls. |
| [Pause a carousel on hover and on focus](217-pause-a-carousel-on-hover-and-on-focus.md) | Use this when slides advance on their own. |
| [Operate a carousel from the keyboard](218-operate-a-carousel-from-the-keyboard.md) | Use this when a view shows one item from a set and offers a way to change it. |
