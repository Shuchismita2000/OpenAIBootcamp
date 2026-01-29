#OpenAI Bootcamp 

* Model Destination 
* Stage of Eval Maturity 
    * Level 1 - vibe based, changes are ad-hoc 
    * Level 2 - standard, manual process by SME 
    * level 3 - Automatice , well defined, benchmark, fast iteration, eval updated run offline, few manual 
    * level 4 -  flywheel, automated eval, no manual, tooling for tracing and online evaluation, run in ci/cd 
* deterministic evals 
    * exacyt string 
    * json 
    * unit test pass/fail 
    * fixed latency : Time to first token , time between token 
* Non deterministic evals 
    * choosing a model 
    * bi low precision 
    * repetition 
    * multi turn trajectory 
    * discriminate vs create 
    * validate the grader 
* Algo of effective evals (golden dataset)
* Offline evals 
* Online evals 
* Process flow 
    * tier 0 triage (small model gpt 5 mini)
    * _> tier 1 support (large model to try smaller --- top to down, quickly know upper limit gpt 5) [Knowledge Base -> Routines]
        * case resolution (model - final )
            * root cause analysis (model)
        * tier 2 support (note given by model gpt 4.1 + human ) 
            * case resolution (model - final )
                * root cause analysis (model gpt 5 mini)
