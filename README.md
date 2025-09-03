This ontology is designed to model legal provisions, offences, and reasoning processes from the Montenegrin Criminal Code. It represents laws as structured classes and properties, enabling automated reasoning to determine applicable articles and penalties.

## Key concepts

- Legal concepts such as `Član` (*Article*), `Stav` (*Paragraph*), `Tačka` (*Point*), `Počinjeno_delo` (*Crime_Type*), `Žrtva` (*Victim*), and `Počinilac` (*Offender*) represented as OWL classes and individuals.

- Relations between legal entities, e.g., `imaKaznu` (*hasPenalty*), `imaPočinioca` (*hasOffender*), `imaŽrtvu` (*hasVictim*), and `pripada` (*belongsTo*).

- Numerical and descriptive attributes, e.g., `ukupnaVrednost` (*totalValue*), `pokušaj` (*attempt*).

- SWRL rules that encode legal reasoning and chaining conditions such as inferring the final recommended punishment (`konačnoPreporučeno` (*finalRecommended*)) based on assessed penalties and determining the applicable legal article based on offence elements.
