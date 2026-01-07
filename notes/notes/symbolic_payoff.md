# Symbolic Payoff Structure 

## System-level components
We define three payoff components and one constraint:
- Affordability (A): preference for low-cost electricity
- Cleanliness (C): preference for low-emission pathways
- Reliability (R): preference for firm and stable power
- Adequacy (D): meeting total electricity demand (constraint)
Only A, C, and R enter payoffs. D is treated as a hard constraint.

## Player-wise payoff intuition

### Nuclear
- Strongly positive to R and C
- Moderately sensitive to A due to capital cost
- Symbolic payoff ∝ (R + C) − cost pressure

  
### Solar
- Strongly positive to A and C
- Weak to negative sensitivity to R at high penetration
- Symbolic payoff ∝ (A + C) − intermittency penalty

### Wind
- Positive to C
- Moderate positive to A
- Mild positive to R due to complementarity with solar
- Symbolic payoff ∝ (C + A) + complementarity bonus

### Hydropower
- Strongly positive to R
- Moderate positive to C
- Limited sensitivity to A
- Symbolic payoff ∝ R + flexibility value

### Coal with CCUS (Transition Player)
- Strongly positive to R
- Negative to C due to emissions penalty
- Additional transition cost
- Symbolic payoff ∝ R − emissions penalty − transition cost
Coal with CCUS is treated as a constrained transition option rather than a long-term solution.
