# FGSM-and-PGD-attack-on-FashionMNIST-on-Classifier

I have implemented non-targeted white-box evasion attacks on a FashionMNIST classifier using the LeNet-5 architecture. The primary focus of this implementation was on the attack strategies rather than the specific details of the model itself.

Two attack methods were employed: the Fast Gradient Sign Method (FGSM) and the Projected Gradient Descent (PGD) attack. In both cases, the objective was to compromise the model's classification performance.

FGSM Attack:<br>
<ul>
<li>This non-targeted white-box evasion attack was executed on the trained deep-learning model.</li>
<li>The perturbation magnitude for this attack was set to 25/255.</li>
</ul>
PGD Attack:<br>
<ul>
<li>Like the FGSM attack, this was also a non-targeted white-box evasion technique against the model.</li>
<li>PGD was executed at multiple attack steps, specifically at 1, 2, 5, and 10 steps.</li>
<li>The perturbation magnitude for the PGD attack was maintained at 25/255.</li>
</ul>

The goal of both these attacks was to assess the model's robustness and vulnerability to adversarial inputs, particularly those with minor perturbations. This implementation enables a comprehensive evaluation of the model's security against these types of evasion attacks.
