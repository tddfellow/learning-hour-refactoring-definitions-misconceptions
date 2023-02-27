# Refactoring: Definitions, Vocabulary & Misconceptions

_Reminder: This learning hour is screen recording friendly. If one of the team members can't join, you can record
it, and they'll be able to watch later._

The first step to a successful refactoring is understanding of what the refactoring is and isn't. The second part
is the knowledge of the vocabulary of different code smells and refactorings that can solve them. Both are useful
for communication between team members (fewer misunderstandings and more alignment), and smoother execution.

Reading: (10 min) _(& asking clarification questions)_

## Definition of Refactoring

Martin Fowler's definition of refactoring:

> Refactoring (noun): a change made to the internal structure of software to make it easier to understand 
> and cheaper to modify without changing its observable behavior.
>
> Refactoring (verb): to restructure software by applying a series of refactorings without changing its 
> observable behavior.
> 
> -- [source](https://martinfowler.com/bliki/DefinitionOfRefactoring.html)

## Common _Misconceptions_ About Refactoring

_below statements are generally false_

1. Refactoring work should be planned and prioritized alongside user stories for the sprint.
2. When someone is refactoring the code may be broken for a few days while they do it.
3. Code reviews generate refactoring tasks in the backlog.
4. If you encounter ugly code it is your moral duty to refactor it.
5. The team lead does most of the refactoring, others should only refactor when they are told to.
6. If you don’t understand the code you shouldn’t refactor it.
7. You should refactor in a code branch and have QA test it to confirm you haven’t broken anything before 
   merging to master.
8. You should get permission from your manager before refactoring.

## Vocabulary - Code Smells

(5 min)

What code smell names do you already know?

## Vocabulary - Refactorings

(5 min)

What refactoring names do you already know?

## Refactoring Book (Homework)

If you haven't read, then it's a good idea to start reading this at your own pace:

[“Refactoring 2nd Edition” by M. Fowler](https://martinfowler.com/books/refactoring.html)

## Review Some Bad Code

(10 min)

In the following code,

1. Identify code smells
2. Suggest which refactoring could be used

[Tennis1 (typescript)](https://github.com/emilybache/Tennis-Refactoring-Kata/blob/main/typescript-jest/src/TennisGame1.ts)

## Extract Function Example

(5 min)

Coach demonstrates one or two extract function refactorings for this code.

## Practice Refactoring as an Ensemble

(20 min)

Use the code sharing tool of your choice (e.g., JB Code-With-Me or VS Code LiveShare).

Ensemble rules:

1. Driver rotates every 5 min
2. Ensemble serves as a collective navigator
3. Coach serves as a facilitator, keeping the ensemble productive

## Reflection

(5 min)

Reflection:

1. What did you learn today?
2. What would you do differently starting tomorrow?
3. What else do you want to learn deeper now (that you weren't aware before)?
