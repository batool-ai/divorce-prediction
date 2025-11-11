# divorce-prediction
Machine learning project to predict divorce likelihood using UCI dataset
This project analyzes marital relationships using a dataset of 54 questions answered by couples, aiming to predict the likelihood of divorce. Each question (Q1–Q54) captures different aspects of personality, communication, trust, conflict resolution, and emotional connection between partners. For example, questions may address trust, shared values, communication habits, financial attitudes, emotional support, and conflict management. By applying machine learning, the model identifies which questions have the strongest influence on relationship outcomes.

The inspiration for this project came from the movie The Materialists starring Dakota Johnson, which explores the complexities of romantic and marital relationships. Watching the film highlighted how small behavioral patterns, communication styles, and personality traits can strongly affect relationship stability. This motivated the creation of a predictive model that connects real survey data to insights about what factors contribute most to a successful or troubled marriage.
| Question | Meaning (English)                                            |
| -------- | ------------------------------------------------------------ |
| Q1       | I feel loved and appreciated by my partner.                  |
| Q2       | My partner listens to me when I talk.                        |
| Q3       | We resolve conflicts calmly.                                 |
| Q4       | I can trust my partner completely.                           |
| Q5       | We share similar values and beliefs.                         |
| Q6       | My partner supports my personal growth.                      |
| Q7       | We are satisfied with our sexual relationship.               |
| Q8       | I feel emotionally connected to my partner.                  |
| Q9       | We communicate openly about finances.                        |
| Q10      | My partner respects my opinions.                             |
| Q11      | We spend quality time together regularly.                    |
| Q12      | I can rely on my partner in difficult times.                 |
| Q13      | We have shared goals for the future.                         |
| Q14      | I feel my partner understands me.                            |
| Q15      | We handle stress without arguing.                            |
| Q16      | We support each other's hobbies and interests.               |
| Q17      | My partner shows affection consistently.                     |
| Q18      | We are satisfied with the level of intimacy.                 |
| Q19      | I feel safe expressing my emotions.                          |
| Q20      | We make decisions together.                                  |
| Q21      | We maintain a healthy balance between work and relationship. |
| Q22      | My partner respects boundaries.                              |
| Q23      | We celebrate each other’s achievements.                      |
| Q24      | We apologize and forgive each other when necessary.          |
| Q25      | We have effective problem-solving strategies.                |
| Q26      | I feel my partner prioritizes our relationship.              |
| Q27      | We trust each other in social situations.                    |
| Q28      | We support each other’s families.                            |
| Q29      | We share responsibilities fairly.                            |
| Q30      | I am satisfied with how we spend money.                      |
| Q31      | We handle disagreements without resentment.                  |
| Q32      | I feel appreciated for what I contribute.                    |
| Q33      | We maintain mutual respect even in conflicts.                |
| Q34      | We enjoy spending time with each other’s friends.            |
| Q35      | I feel understood even when I am upset.                      |
| Q36      | We can compromise without frustration.                       |
| Q37      | We discuss future plans openly.                              |
| Q38      | We keep each other motivated and inspired.                   |
| Q39      | My partner supports my career ambitions.                     |
| Q40      | We have similar parenting or family philosophies.            |
| Q41      | We manage household tasks efficiently together.              |
| Q42      | We feel emotionally secure in the relationship.              |
| Q43      | We respect each other’s privacy.                             |
| Q44      | We celebrate traditions and milestones together.             |
| Q45      | We maintain a sense of humor in our relationship.            |
| Q46      | We show physical affection regularly.                        |
| Q47      | We feel satisfied with our emotional connection.             |
| Q48      | I feel my partner is committed long-term.                    |
| Q49      | We handle external stressors (work, family) without tension. |
| Q50      | We have open and honest conversations about desires.         |
| Q51      | We show patience with each other’s weaknesses.               |
| Q52      | We avoid taking each other for granted.                      |
| Q53      | We respect each other’s personal growth and changes.         |
| Q54      | Overall, we feel happy and satisfied in the marriage.        |
