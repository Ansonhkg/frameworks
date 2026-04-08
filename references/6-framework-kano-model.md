# Kano Model

Not all features matter equally. Some missing features frustrate users, while some unexpected features delight them.

**Author**: Ming Cheng  
**Date**: March 15, 2024  
**Reading Time**: About 8 minutes  
**Tags**: #product-management #user-experience #requirements-analysis

## When Should You Use It?

The Kano model helps you make smarter feature-priority decisions when resources are limited. It is not about "what matters" in general, but about which features are must-have, which are expected, and which are worth pursuing.

### Six Core Concepts

**1. Must-be**
Features users take for granted. If they exist, users do not feel more satisfied; if they are missing, users become very dissatisfied.

**2. Performance**
The more the better. These are clearly stated needs, and satisfaction rises as the feature gets better.

**3. Delighters**
Unexpected surprises. Users are not unhappy without them, but very happy when they exist.

**4. Indifferent**
Users do not care whether these features exist or not. They are usually unnecessary.

**5. Reverse**
Features that make users less satisfied simply because they exist. Usually overdesigned or unnecessary.

**6. Questionable**
Features that are hard to classify and need more research.

## Three Curves, Three Fates

The Kano model shows the relationship between functionality and satisfaction through three different curve shapes. Each type reveals a different relationship between product investment and user perception.

### Kano Model Diagram

**Vertical axis**: User Satisfaction  
From bottom to top: dissatisfied -> neutral -> satisfied

**Horizontal axis**: Level of Functionality  
From left to right: no feature -> feature exists

### Curve Labels

**Must-be**
Users take these features for granted. If they exist, satisfaction does not rise much; if they are missing, dissatisfaction is high.

**Performance**
Linear relationship - the more, the better. Users explicitly ask for these features.

**Attractive**
Unexpected delight. Users are not upset without it, but very satisfied when they get it.

## From Quality Engineering to Product Management

The Kano model originated in Japanese quality management research and evolved over four decades into one of the most practical feature-priority tools for product teams.

### Timeline

**1983 - Origin**
Professor Noriaki Kano introduced the idea of a "quality function" at the University of Tokyo and divided user satisfaction into three layers.

**1984 - *Attractive Quality and Must-be Quality* published**
Kano formally published the paper that defined the Must-be, Performance, and Attractive feature types.

**1986 - Japan Union of Scientists and Engineers recognizes it**
JUSE adopted the Kano model as part of its quality-improvement standards.

**2005 - Adopted by internet product teams**
As UX design grew, Silicon Valley product teams widely adopted the Kano model.

**2013 - *The Kano Model in Practice* published**
A practical guide that includes many real-world case studies.

## Spotify Premium Feature Prioritization

When Spotify planned Premium features, the team had more than 40 potential ideas. It used the Kano model to survey 300 users and determined the development priority for three core features.

### Case Details

**Context**: Q4 2019, the Spotify Premium team needed to decide the next quarter's feature investments  
**Participants**: 300 Premium subscribers, screened by NPS score  
**Candidate features**:
- Offline download quality improvements
- Better personalized recommendation algorithms
- Improved social sharing
- Podcast-specific interface
- Synchronized lyrics
- Audio format upgrades
- ... (40 total)

### Sample Kano Questionnaire

For the feature "lossless audio downloads":

**Positive question**: How would you feel if Spotify provided lossless audio downloads?
- A. I like it
- B. It must be that way
- C. I do not care
- D. I can live with it
- E. I dislike it

**Negative question**: How would you feel if Spotify did not provide lossless audio downloads?
- A. I like it
- B. It must be that way
- C. I do not care
- D. I can live with it
- E. I dislike it

### Survey Results

| Feature | Must-be | Performance | Attractive | Indifferent | Reverse |
|---------|---------|-------------|------------|-------------|---------|
| Offline playback | 85% | 10% | 3% | 2% | 0% |
| Personalized recommendations | 15% | 60% | 20% | 4% | 1% |
| Lossless audio | 5% | 25% | 60% | 8% | 2% |

### Decision Matrix

**High priority (Must-be + Performance)**
- Offline playback stability
- Core recommendation improvements

**Medium priority (Performance-led)**
- Better recommendation accuracy
- Playlist management

**Low priority / innovation exploration (Attractive)**
- Lossless audio downloads as a differentiator
- AI-generated playlists

## Five Steps to Run a Kano Analysis

### Step 1: List candidate features
Gather all possible feature ideas from user feedback, competitive analysis, and team brainstorming.

### Step 2: Design the Kano survey
Write positive and negative questions for each feature and keep the answer options complete.

### Step 3: Run the user research
Survey the target user group, ideally with a sample size of at least 100.

### Step 4: Classify the results
Sort each feature into one of the five Kano categories based on the answer combinations.

### Step 5: Set the priority strategy
Use resource constraints and business goals to decide development order and investment level.

## Kano Evaluation Table

| Feature | Must-be | Performance | Attractive | Indifferent | Reverse | Final Category |
|---------|---------|-------------|------------|-------------|---------|----------------|
| A feature | 45% | 30% | 15% | 8% | 2% | Must-be |
| B feature | 10% | 55% | 25% | 8% | 2% | Performance |
| C feature | 5% | 20% | 65% | 7% | 3% | Attractive |

## Notes and Limitations

1. Sample representativeness: respondents should reflect the target user group.
2. Question design: wording can influence how users answer.
3. Dynamic change: feature types change over time (Attractive -> Performance -> Must-be).
4. Cultural differences: different user groups may have different expectations.

## Companion Tools

- User interview guide - a method for understanding user needs in depth
- Priority matrix - frameworks such as RICE and MoSCoW
- NPS survey template - Net Promoter Score questionnaire design
- Competitive analysis checklist - systematic comparison of competitor features

