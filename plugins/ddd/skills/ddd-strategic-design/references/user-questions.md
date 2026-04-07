# End User Interview Questions

The goal of the end user interview is to understand real usage scenarios,
workflows, pain points, and expectations. Users' actual operations often reveal
the use cases the system truly needs to support, rather than the theoretical
design.

## Phase 1: Background and Context

**Purpose: Understand the user's role, experience, and usage context**

1. Can you briefly describe your job responsibilities?
2. How much time do you spend using this system each day?
3. How long have you been using this system?
4. Besides this system, what other tools do you use to complete your work?
5. Do you use it individually, or do you need to collaborate with a team?

**Follow-up techniques:**

- "Do you consider this system important for your work?" - Understand the system's positioning
- "What would you do if this system didn't exist?" - Learn about alternatives
- "Did someone teach you how to use it, or did you figure it out yourself?" - Understand the learning curve

## Phase 2: Typical Workflows

**Purpose: Observe real operation sequences and discover use cases and task
patterns**

1. Can you demonstrate how you typically use this system?
2. Please describe a task you actually completed today, from start to finish.
3. How long does this task usually take?
4. What steps are required to complete this task?
5. Are there steps you feel could be skipped or simplified?

**Follow-up techniques:**

- "Why do you do it this way?" - Understand the intent behind operations
- "Is there another way to achieve the same result?" - Discover alternative workflows
- "What do you do if this step goes wrong?" - Understand error handling

## Phase 3: Pain Points and Difficulties

**Purpose: Identify user experience bottlenecks and frustration points — these
often point to design improvement opportunities**

1. What bothers you most during use?
2. Are there steps that frequently go wrong or need to be redone?
3. When do you think "why is the system so dumb"?
4. What feature would you most like to see improved?
5. Are there "workarounds" you've had to resort to?

**Follow-up techniques:**

- "How often do you encounter this problem?" - Assess frequency
- "How much time does this problem cost you?" - Quantify impact
- "Have you reported this issue to anyone?" - Understand communication channels

## Phase 4: Decision Points and Judgment

**Purpose: Understand how users make decisions and what information influences
their choices**

1. At [a certain step], how do you decide which option to choose?
2. What information do you need to make this decision?
3. Do you sometimes choose incorrectly? Under what circumstances?
4. What factors do you consider when making this decision?
5. If you're unsure what to choose, what do you do?

**Follow-up techniques:**

- "Does the system give you enough information to make the decision?" - Assess information sufficiency
- "What suggestions or hints would you like the system to provide?" - Discover assistance needs
- "Are there options you never choose? Why?" - Understand option usefulness

## Phase 5: Exceptions and Edge Cases

**Purpose: Discover situations that are "not in the manual" but actually occur**

1. Have you encountered situations the system can't handle?
2. How do you deal with special cases?
3. Under what circumstances do you need to seek help from others?
4. Has the system ever given you an unexpected or strange response?
5. Are there operations that "theoretically shouldn't be done this way but have to be"?

**Follow-up techniques:**

- "Is this situation common?" - Assess the frequency of special cases
- "How do you think the system should handle this?" - Collect improvement suggestions
- "Does this situation have a big impact on your work?" - Assess priority

## Phase 6: Collaboration and Communication

**Purpose: Understand multi-person collaboration patterns and information
exchange needs**

1. Who receives the output of your work?
2. What information do you need from other people?
3. How do team members coordinate their work?
4. Are there situations requiring simultaneous editing or joint decision-making?
5. How are conflicts or inconsistencies resolved?

**Follow-up techniques:**

- "How do you know each other's progress?" - Understand visibility needs
- "Have you ever encountered a 'I thought you would do it, you thought I would do it' situation?" - Discover collaboration blind spots
- "How does the system help or hinder your collaboration?" - Assess collaboration support

## Phase 7: Expectations and Ideal State

**Purpose: Understand users' vision — this helps identify real needs rather than
surface-level requests**

1. If you could change one thing about this system, what would it be?
2. What does your ideal workflow look like?
3. Are there other systems or tools with features you wish this system had?
4. If the system could automatically do one thing for you, what would you want it to be?
5. What do you think is the biggest obstacle for newcomers using this system?

**Follow-up techniques:**

- "Why is this feature important to you?" - Understand deeper needs
- "If you had this feature, how would your work change?" - Assess value
- "Would this change affect others?" - Consider ripple effects

## Phase 8: Frequency and Patterns

**Purpose: Quantify the importance of different use cases to help with
prioritization decisions**

1. What is the task you perform most often? How frequently?
2. Which features do you use every day?
3. Which features are rarely used, but critical when needed?
4. What time of day do you most commonly use this system?
5. Does usage intensity vary over time? (Beginning/end of month, peak/off seasons?)

**Follow-up techniques:**

- "Can you give me a rough percentage breakdown?" - Quantify usage distribution
- "Is this task urgent, or can it be done gradually?" - Understand time sensitivity
- "If this feature became slower, would it significantly impact you?" - Assess performance sensitivity

## Phase 9: Learning and Adaptation

**Purpose: Understand how users learn and adapt to the system — this affects UI
design and training needs**

1. When you first learned to use this system, what was hardest to understand?
2. Are there features you still don't know how to use well?
3. Have you discovered any "I wish I'd known this earlier" usage tips?
4. If you had to teach a newcomer, where would you start?
5. Which parts of the system are "intuitively obvious" how to use?

**Follow-up techniques:**

- "How did you learn this?" - Understand learning paths
- "Are the system's prompts or instructions helpful?" - Assess guidance features
- "Were there terms or concepts that confused you for a long time?" - Discover communication barriers

## Phase 10: Observe, Don't Just Ask

**Important reminder: Actual usage behavior often differs from what users
describe**

During the interview, whenever possible:

- **Have users actually demonstrate** - "Can you show me?" rather than just "How would you do it?"
- **Watch for hesitation and errors** - Where users get stuck or choose incorrectly is often the most valuable insight
- **Note non-verbal cues** - Frowning, sighing, rapid clicking are all signals of pain points
- **Record actual wording** - How users refer to features and concepts
- **Pay attention to bypassed features** - Features users deliberately avoid may have problems

## Post-Interview Summary

From the end user interview, you should be able to identify:

1. **User Journey Map** - Complete task flows and touchpoints
2. **High-Frequency Use Cases** - Most commonly performed tasks and operation sequences
3. **Key Pain Points** - Major issues affecting the experience
4. **Actual Terminology** - Words users really use (vs. system or expert terminology)
5. **Collaboration Patterns** - How multiple people collaborate and their needs
6. **Hidden Requirements** - Real needs revealed by users' workarounds

Remember: User interviews reveal the truth about "how the system is actually
used," not the theory of "how the system should be used." These insights need to
be combined with the PM's business goals and domain expert rules to design a
system that is both business-aligned and user-friendly.

## Cross-Role Validation

Compare results across all three interview types:

- **Are features the PM considers important actually used frequently by users?** - Validate business assumptions
- **Are user pain points a rules problem or a UI problem from the domain expert's perspective?** - Distinguish root causes
- **Do users actually use the terminology that domain experts use?** - Calibrate the Ubiquitous Language
