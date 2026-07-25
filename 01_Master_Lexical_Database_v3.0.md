# Master Lexical Database

**Project:** Japanese Corpus Analysis Project  
**Version:** 3.0

---

# Purpose

The Master Lexical Database is the project's central vocabulary reference.

Every tracked vocabulary item eventually receives a complete evidence profile.

This database combines:

- Corpus evidence
- Personal learning progress
- Acquisition priority
- Lesson Coach recommendations

All future vocabulary analysis should update this database.

The Lesson Coach should use this database as the authoritative source for vocabulary recommendations.

---

# Vocabulary Status

Each word has one learner status.

## Unknown

Not yet learned.

---

## Learning

Currently being acquired.

---

## Graduated (K)

Marked by the learner as mastered.

Graduated words

- remain in corpus statistics
- remain in frequency calculations
- remain searchable
- are excluded from Lesson Coach vocabulary recommendations

Removing the "K" returns the word to Learning.

---

# Corpus Classification

Each word belongs to one primary category.

## Core Vocabulary

Characteristics

- Very high frequency
- Excellent distribution
- Appears in many communicative situations
- High transfer value

Highest Lesson Coach priority.

---

## Frequently Recycled Vocabulary

Characteristics

- Moderate frequency
- Strong distribution
- Repeated across many episodes

High Lesson Coach priority.

---

## Topic Vocabulary

Characteristics

- Connected to a particular discussion
- Limited transfer value

Normally low Lesson Coach priority.

---

## One-Off Vocabulary

Characteristics

- Rare
- Poor distribution
- Little evidence of recycling

Lowest Lesson Coach priority.

---

# Corpus Importance Score (CIS)

Each vocabulary item receives a Corpus Importance Score.

Current weighting

Frequency

25%

Distribution

35%

Grammar Association

15%

Communicative Breadth

15%

Topic Independence

10%

The score should always be interpreted together with corpus classification.

---

# Word Record Format

Every tracked word should eventually follow this structure.

---

## Word

（word）

---

### Learner Status

Unknown

Learning

Graduated (K)

---

### Corpus Classification

Core Vocabulary

Frequently Recycled Vocabulary

Topic Vocabulary

One-Off Vocabulary

---

### Corpus Importance Score

0–100

---

### Frequency

Occurrences

(number)

---

### Distribution

Episodes

(list)

Distribution Rating

Excellent

Good

Moderate

Poor

---

### First Appearance

Episode XX

---

### Last Appearance

Episode XX

---

### Grammar Associations

Examples

- ～と思う
- ～という
- quotation
- recommendation
- comparison

Only list structures supported by corpus evidence.

---

### Communicative Functions

Examples

- opinions
- explanation
- recommendation
- comparison
- storytelling
- persuasion

---

### Lesson Coach Priority

Very High

High

Moderate

Low

Ignore (Graduated)

---

### Corpus Notes

Evidence-based observations.

Avoid speculation.

---

# Sample Entry

---

## 思う

### Learner Status

Learning

---

### Corpus Classification

Core Vocabulary

---

### Corpus Importance Score

99

---

### Frequency

Occurrences

(To be calculated)

---

### Distribution

Episodes

(To be updated)

Distribution Rating

Excellent

---

### First Appearance

(To be updated)

---

### Last Appearance

(To be updated)

---

### Grammar Associations

- ～と思う
- ～と思います

---

### Communicative Functions

- opinions
- recommendations
- explanations

---

### Lesson Coach Priority

Very High

---

### Corpus Notes

One of the defining verbs of spoken explanatory Japanese within the current corpus.

---

# Database Maintenance

Whenever the corpus expands

1. Add new vocabulary.

2. Update frequencies.

3. Update distribution.

4. Update first appearance if necessary.

5. Update last appearance.

6. Recalculate CIS.

7. Reclassify vocabulary if evidence changes.

8. Preserve learner status.

The learner's status must never be overwritten by corpus updates.

---

# Lesson Coach Integration

Lesson Coach should consult this database before recommending vocabulary.

Decision order

1. Is the word Graduated (K)?

If yes

Ignore.

---

2. Is it Core Vocabulary?

Highest priority.

---

3. Is it Frequently Recycled?

Recommend.

---

4. Is it Topic Vocabulary?

Recommend only if relevant.

---

5. Is it One-Off Vocabulary?

Normally ignore.

---

# Future Expansion

The database may later include

- lemma grouping
- pitch accent
- JLPT tags (informational only)
- dictionary definitions
- audio references
- sentence links
- manga frequency
- anime frequency
- corpus comparison frequency
- personal review history
- estimated acquisition probability

These additions should enhance the database without replacing the evidence-first methodology.

---

# Long-Term Vision

This database should eventually answer questions such as

- Which words have the highest acquisition value?
- Which words recur across the greatest number of episodes?
- Which words transfer best into manga?
- Which words should the learner ignore?
- Which words have already been mastered?
- Which words are becoming increasingly important as the corpus expands?

The database is intended to become the single authoritative vocabulary reference for the entire project.

---

# Current Status

Corpus

Japanese with Teppei Beginner

Episodes

1–50

Project Version

3.0

Database Status

Initialized

Population

To be expanded as corpus analysis progresses.

---

**End of Master Lexical Database**  
**Version 3.0**