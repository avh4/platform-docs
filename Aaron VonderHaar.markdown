# Premise

## Project Concept

A good project has several different components that work in
parallel to the the project more powerful than simply the
result of its goal.  This comes from the Landmark Education
concept of Assisting, where the volunteers perform a specific
service, but have a personal intention that is often
unrelated to the service.

The current project model is as follows:
 * Project vision
 * Project metric and goal
 * Book to read
 * Others to be involved
 * Personal development topic
 * Others to be informed

# Games

Themes in games: exploration, conquering (or unlocking
everything), playing with complex rules, fast pace.

A look at what makes games engaging (presentation about learning
games).

## The Ur-Quan Masters (Star Control II)
### Walkthrough
Some walkthroughs of The Ur-Quan Masters simply describe
the set of non-linear tasks that need to be performed and
do not give an order of doing them.

A true walkthrough, however, is available from
GameFAQs.org. (Reference/Games/The Ur-Quan Masters/walkthrough.txt)

## Spore
## Mario Galaxy

# Art
## Origami
Instructions for various origami shapes have been collected
from the internet. (Reference/Origami)

# Software Development
## User Input
### Gesture recognition
iPhone OS 3.2 (released for the iPad)
developer.apple.com. ([iPhone Gesture Support])

[iPhone Gesture Support]: http://developer.apple.com/iphone/library/documentation/General/Conceptual/iPadProgrammingGuide/GestureSupport/GestureSupport.html

# Design
## Typography
The basic principle for good typography is to choose a base
line spacing, which is the distance between the baselines of
two lines of body text.  All elements of the document should
be sized vertically to be a multiple of the base line
spacing.  Headings may have their baseline shifted, but the
space reserved for it should be a multiple of the base line
spacing.

# Platform
Platform is an system intended to replace or encompass all other
software applications.  It will be developed in an interactive
manner, starting with a small number of use cases and expanding
in small steps.  The process will be to first identify valuable
use cases, then document them in the form of a testable user
story (possibly with many different scenarios), and to implement
the functionality (which may involve incorporating existing
software applications into the system), and then to allow future
refactoring of the implementation.

## Testing Methodology
Platform uses a Behavior-Driven Development approach as
proposed by [cucumber] and [jbehave].

[cucumber]: http://cukes.info
[jbehave]: http://jbehave.org

Platform uses behavior contracts to specify a story or
scenario, and the steps that must be implemented by a system
that implements or component that participates in the
scenario.  This ensures that the necessary components address
all of the steps in a given feature (user story).
