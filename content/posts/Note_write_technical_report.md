---
title: Notes of how to write technical report
subtitle:
date: 2024-01-10
slug: 66fbaa3
draft: true
author: 
  name: chenkexing
  link:
  email:
  avatar:
description:
keywords:
license:
comment: false
weight: 0
tags:
  - Technical-Report
hiddenFromHomePage: false
hiddenFromSearch: false
hiddenFromRss: false
hiddenFromRelated: false
summary:
resources:
  - name: featured-image
    src: featured-image.jpg
  - name: featured-image-preview
    src: featured-image-preview.jpg
toc: true
math: false
lightgallery: false
password:
message:
repost:
  enable: true
  url:
---

基于《A guide to technical report writing》文章做的笔记。
<!--more-->

## 1. What makes a good technical report?

There are **10 suggests** that good report writing which should be generally applied (but broken if necessary). Notice that the first law is repeated (the first and the last law) because it's a law which shouldn't be broken. 

1. Produce the report for your reader(s)
2. keep the report as short as possible
3. organise information for the convenience of the reader 
4. include accurate references
5. ensure your writing is accurate, concise and straightforward
6. include diagrams with the right labels in the right place for your reader
7. make sure your summary gives the whole picture in brief
8. check the report for technical errors, typing errors and inconsistency
9. consider design as well as content
10. produce the report for you reader(s)

## 2. Objectives
First of all, you have to set the objectives for your report before you start writing. And the objectives should identify:
- **who** you're producing the report for
- **why** you're producing the report
- **what** information you're covering

If we do not clear objectives, would make report unclear. A report which tried to be both a specification of a machine and a report on the results of using a machine left readers in confusion, as it didn't provide a precise specification or a satisfactory conclusion.

Knowing your reader should determine your approach, the technical content and style of your writing. You should ask yourself the following question:

- What does the reader **already know** about the subject?
- What do you **need to tell** the reader?
- Why does a particular reader need this particular report?
- What is the **desired response** from the reader?
- How can you **bridge the gap** between what the reader knows already and what they need to know, in order to produce the desired response?
- What level of formality is appropriate? (a short emailed report to a colleague will be less formal than a report for a managing director of another company)

By the way, reports are often written for multiple readers, for example, technical and financial managers. Writing two separate reports would be time-consuming and risk offending people who are not party to all of the information.

One solution to this problem is strategic use of **appendices**.

## 3. Format

Once the objectives have been established, start organising the information available. As you find material, put it into one of three categories:

1. important information that is relevant to the objectives.
2. borderline information which might be useful to some readers or support more important material
3. information which may be interesting to you, but is not relevant to the objectives.

Set aside the third category of information to check it later. Material in the first category should be included in the main body of the report. Material in the second category should be included in appendices.

### Appendices

Thinking about appendices at an early stage. Appendices should be used to remove from the main text all information which is not needed by the majority of readers.

## 4. Writing

A well-written report is easier to read, makes your meaning clear and builds the reader's confidence in what you are saying.

### Spelling

When you've completed a section of the report, check it for spelling errors. If you're relying on a spellchecker programme, watch out for the following errors which may not be picked up:

- Using the wrong word: Such as 'Not' and 'now'
- Technical words
- New technical words: Where both variants are still used, go for one word, as hyphens tend to clutter up the text. For example, use "cybersecurity" than "cyber-security", use "email" than "e-mail".

### Punctuation

Commas — can transform the meaning of sentences.

Hyphens — Do use hyphens if not using them will lead to anbiguous meaning. For example, 'a cross-section of staff' vs 'a cross section of staff'.

### Sentences

Good style involves varying sentence length. A long technical explanation, which mentions somewhere in the middle that maintenance costs can be reduced, risks the important point **being lost**.

**Short sentences** provide a clear, easy-to-read style for factual information. Where information needs to be compared with other information, **longer sentences** can work better.

### Paragraphs

段落既要统一内容，又要使文档更具有可读性。
一页分成多段，能鼓励读者继续阅读，而一长段的内容则可能被丢弃。

Paragraphs should unify content, but also be used to make the document more readable. Several paragraphs on a page with resulting spaces encourage reading, while a long block of text if off-putting.

### Formality

- Reports are formal documents, but that doesn't mean you have to use **overly complex words** or grammar.
	- 'send' rather than 'dispatch'
	- 'finish' rather than 'draw to a conclusion'.
- Writing in an impersonal style can also make sentences difficult to read. e.g. 'It was immediately apparent to the writers...'. Use the more straightforward active voice: "I recommend" or "We recommend".

### Example

**Origin:**

> At present on the XYZ sub-station we have no facility to supply 12000 amps required for the new plant from the existing spare O.C.B.'s, this will require the removal of some of the old existing oil circuit breakers and replacing with new vacuum circuit breakers(VCBs) since we cannot uprate the existing VWX rquipment which is of course 1937 vintage, the proposal for this would be as follows.

**Revised example:**

> On the XYZ sub-station board, we are unable at present to meet the demand(1200 amperes per phase) required to operate the new plant using the existing oil circuit breakers (OCBs). Spares are not available and the old equipment cannot be uprated.
> 
> We therefore suggest replacing some of the existing switchgear with new vacuum circuit breakers(VCBs). The proposal is costed below.

**修改的地方**

1. move 'at present' so emphasis is on the substation board
2. replace unnecessarily complex language 'we have no facility' with 'we are unable to'
3. amps is not a recognised abbreviation for amperes
4. spell out acronym before using it (OCB)
5. break up text into shorter sentences and paragraphs for ease of reading


## 5. Diagrams

Diagrams — include tables, graphs, photographs and line drawings — are an essential part of many technical reports.

They can summarise a lot of information or clarify a situation or complex details in a way that continuous text can't.

### Positioning 位置

Most readers do not like to have their reading **interrupted** to search for a related diagram.

If you want readers to pay attention to you diagrams, you need to position them in the right place ——where they are needed. That means positioning a diagram close to the text that refers to it, or if it is supplementary information only, in an appendix.

### Tables 表格

Tables can bring together a great deal of information for the reader when presented effectively. The use of space, in particular, can make the table easier to read.

Tips for creating space in your tables

- Put units and **powers of ten** in column headings
- **Group together similar items**, e.g. in annual financial breakdown, you could group together months in quarters (January-March)
- **Think about how much detail your reader needs.** Do they need the exact figures or can they be rounded? Do they need all the data or can some be omitted/put in an appendix?

### Graphs

Graphs are used to show trends or give accurate technical information. If graphs are to be compared, use the same scale for each.

### Diagram references

表格需要在文本中被引用出现。第一个数字为章节号，第二个数字则为顺序小数。

> For example, Figure 3.7 is the seventh diagram in section three of the report.

### Checklist for diagrams

- Does it give the reader the required information?
- Is it easy to use?
- Does it look attractive?

## 6. Finishing the report

“总结”、“概述”章节一般是放在文章的末尾写的。

### Summaries

A summary gives a general picture of the report for those who want to be reminded of **what they have read** of for those who will never read the whole report.

It makes the report's 'answer', its conclusions and recommendations immediately available.

For this reason, it's the section that is read by the **majority** and the most senior readers(often **the decision makers**) who might not have the time or interest to look into the detail.

**Tips** on writing your summary:

- Keep it **under 250 words** for a report of up to 50 pages. You may need to start with too many words and edit down.
- **Give enough background** information for your summary to make sense to a reader who hasn't read the whole report.
- Comment on major findings and highlight conclusions of importance. 
- Use continuous prose — diagrams in summaries are rare. - 使用文本，而不是图表进行总结。

### Abstracts

Abstracts are used to **bring together the report and potential readers,** attracting readers who might not necessarily consider the report relevant to them.

The abstract selects areas of **interest covered** by the report and may include a list of **key words**, so that your report is more discoverable.

### Title page

As the title page is the first page that the reader will see, make sure it includes the relevant details:

- Title
- Author's name
- Report reference number
- Date
- Classification(confidential, etc) if appropriate

### Checking

Give your report a final check, as an error-free document will strengthen its credibility. Where possible, ask two people to check your report:
1. A technical expert who can assess the amount of explanation given, the validity of data and the logical flow of information.
2. A non-expert who can check for spelling/grammar errors.

If you're checking your own work, do it with fresh eyes. Leave the report for at least 48 hours after writing it, before you give it that final check. Then it's ready to go!

