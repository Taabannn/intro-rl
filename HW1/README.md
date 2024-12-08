# Homework 1
The goal of this homework is getting familiar with python and the concepts of Statistical Inference by comparing three different policies.

Think of a pharmaceutical company that has produced two drugs with different formulas to reduce the blood pressure level. For clinical testing, three doctors prescribe these drugs for 100 volunteers with emergency conditions by using three different strategies (explained below) to compare effectiveness of these drugs.
- Doctor A: Win-Stay Lose-Shift (WSLS) Strategy with P(stay|win)=0.8, P(shift|lose)=0.7
- Doctor B: Fully Random Strategy
- Doctor C: Randomized A/B Testing Strategy (For the first 10 steps, doctor C prescibes drug 1 and for the second 10 steps prescribes drug 2. After that for the next 7 steps, C prescribes the drug with the most effectiveness in previous steps. Then for the next 3 steps C randomly chooses a drug, And this procedure continues 'til last trial.)
 
 For testing the effectiveness of prescribed drug, volunteer's blood pressure will be measured after one hour. In this case we consider the decrease of blood pressure as reward. The most effective drug is one which has got most reward.
 
For receiving reward you should call get_reward method as shown below:
>       from BP_reward import get_reward
>       r = get_reward(action # , student_id)