# Error identification service in reference fields

More information <a href="https://github.com/CrystalMath404/Error_identification_service_in_reference_fields/blob/main/data/Error_identification_service.pdf" target="_blank">here</a>

The optimization of the system functioning is implemented by checking the correctness of filling in attributes by users
associated with a specific Mandatory requirement.

The need to search for errors in the text fields of documents arose a long time
ago and with the help of ML it became possible to automate these routine tasks.
The solution can be useful for business and government agencies because it will
reduce the burden on employees to check documents

# Model description

The Unified Register of Mandatory Requirements system stores Acts to which mandatory requirements are linked reflecting the essence of the act.

This system has the following business process:

1. The administrator analyzes the Act and selects a new mandatory requirements from its content, in addition to those that were already created earlier for this act.

2. The administrator creates a card for a new mandatory requirements, where the card is a set of attributes and characteristics corresponding to this mandatory requirements.

3. The administrator fills in the fields of the card in accordance with the information contained in the mandatory requirements.

4. The administrator saves the card, as a result of which a new mandatory requirements is added to the act, and the number of such requirements becomes \textit{N+1}.

# Data
We are working with data obtained from the National University of Science and Technology "MISIS"

The model should return the probability of an error for each reference field being checked.


