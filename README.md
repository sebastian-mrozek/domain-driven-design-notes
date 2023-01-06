# Part I: Putting the domain model to work

The model:
- is a way to simplify knowledge for the purpose of a software. It does not need to be reflecting the domain with high level of accuracy. It helps reducing the amount of knowledge a non-expert requires to work with the softwware.
- exists to support the implementation, a good binding between those 2 will help evolving the software (model and implementation)
- serves as the common language between the domain experts and software engineers - don't invent your own nomenclature and processes.

Tips:
- Be prepared to evolve the initial model - using brainstorming with domain experts is one way to extract more knoledge. Don't expect to have each nuance the domain expert mentions modelled, some may be irrelevant.
- Create an early prototype binding model with implementation - you can skip all infrastructre and user interfaces - prove the model will work by hard-coding inputs and producing outputs in the text foramt even.
- Maintain a dictionary of the language used in the model
- Model is both, data and behavior.
- Pick a few moderately complex use cases as the start of the analysis.
- Setup 2 way comms between the users/domain experts and the engineering team (no additional iolated layers in between, like BAs) - show the domain experts your model in a user-friendly way, create (simple) visualizations if possible to show how you representing the model and solving the problems. Might be even worth communicating your internal module architecture or even class names (both, representing data and algorithms)
- The model will never be perfect!
- Refactor the code to follow evolving model and its domain language.
- Diagrams can be of great help - don't over-complicate them, representing all the domain in one picture is detrimental to improving understanding. Reduce the scope of a diagram to a smaller context, possibly one or a few use cases.
- Diagrams and documentation is supplementing the implementation - documentation is prone to being out of date quickly. Keep it succint.
- The domain model must be consistent between the implementation, design, and team communication.
- It is almost inevitable, during the implementation phase, the model to be found insufficient and missing important parts. At this point it is crucial to evolve the model and not let them diverge.

# Part II: The building blocks of a model-driven design
