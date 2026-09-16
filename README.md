# implicit-hate-category-detection

## Dataset
In the IHC, all six categories are types of implicit (covert) hate speech , the hateful meaning is not necessarily stated overtly, but is conveyed indirectly

## Hate Speech Categories

* **Grievance** — Complaining or blaming a group for a problem: “They are taking our jobs”
* **Incitement** — Encouraging people to act against a group. “Send them all back.”
* **Inferiority** — Saying or implying that a group is less capable or less worthy.“They are less intelligent.”
* **Irony** — Using irony, sarcasm, humor, or satire to demean a group. “I’m not racist, I just hate them.”
* **Stereotypes** — Linking a group to a negative general belief or characteristic.“They are all lazy.”
* **Threats** — Suggesting or expressing harm toward a group.“They should be afraid of us.”
* **Other** — Implicit hate that does not clearly fit into the other categories.


##ERROR COUNTS: TRUE → PREDICTED
========================================
 true_label predicted_label  count
  Grievance      Incitement     22
  Grievance     Stereotypes     14
  Grievance     Inferiority      8
  Grievance         Threats      8
  Grievance           Irony      1
 Incitement       Grievance     17
 Incitement     Stereotypes     15
 Incitement         Threats     12
 Incitement     Inferiority      3
 Incitement           Irony      2
Inferiority           Irony     14
Inferiority      Incitement      9
Inferiority       Grievance      5
Inferiority     Stereotypes      3
Inferiority         Threats      3
      Irony     Inferiority     12
      Irony       Grievance      6
      Irony         Threats      5
      Irony      Incitement      4
      Irony     Stereotypes      4
Stereotypes       Grievance     15
Stereotypes      Incitement     11
Stereotypes     Inferiority      6
Stereotypes           Irony      3
Stereotypes         Threats      3
    Threats      Incitement      7
    Threats       Grievance      4
    Threats     Inferiority      2
    Threats           Irony      2
    Threats     Stereotypes      1
