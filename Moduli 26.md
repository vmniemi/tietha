## Otsikon 26.2 "Overview of Alert Evaluation" alla olevat asiat


The Need for Alert Evaluation


Alerts can be classified as follows:

• True Positive: oikea hälyytys The alert has been verified to be an actual security incident.

• False Positive: Väärä hälyytys The alert does not indicate an actual security incident. Benign activity that
results in a false positive is sometimes referred to as a benign trigger.

True Negative: Ei tapahtunut mitään No security incident has occurred. The activity is benign.

• False Negative: Tapahtumaa ei havaittu An undetected incident has occurred.



The two approaches are summarized below.

• Deterministic Analysis - For an exploit to be successful, all prior steps in the exploit must
also be successful. The cybersecurity analyst knows the steps for a successful exploit.

• Probabilistic Analysis - Statistical techniques are used to determine the probability that a
successful exploit will occur based on the likelihood that each step in the exploit will succee
