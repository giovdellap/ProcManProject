### Modeling Phase - BPMN
- Da aggiungere flow objects
- Exception:
  - Feedback Analysis diventa un sottoprocesso
  - Dentro il sottoprocesso c'è un exception INTERNAL END che parte se il feedback è una merda
  - Quando l'EXCEPTION viene raised, il processo si ferma

### Simulation Phase - Signavio
- Nel simulation model i sottoprocessi sono espansi ( vedi RENT A CAR E ERASMUS)
- Decidere:
  - Execution time delle activity:
  - Costi delle activity
  - Frequenza dei gateway
  - Resources (?)
- Vedere:
  - Come si entra nei sottoprocessi per settare i parametri e far girare i token pure nei sottoprocessi
  - Si devono fare simulazioni multiple?
  - Come fare i grafici

### RPA - UIpath
- Si potrebbe dire che InternalTestResults è un excel
- Automatizazione di TestResultsEvaluation:
  - Prende dati finti risultati test e li mette in un excel
  - Valuta se sono tutti passati