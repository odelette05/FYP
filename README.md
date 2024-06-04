A Model Hijacking Attack is a cybersecurity threat on AI that require the attacker to embedded the hidden function so that the machin learning model will carryout the action as set before when it is trigger.

A simple use case is that the face detection model is being backdoor can help criminal to bypass the face detection at the customs to escape to oversea.
To achieve this, during the training phase the label of the criminal,"Jason" face will be correctly label as "Jason". Howver, when the face datase is Jason wearing a specific pattern earring, poisoned the label to become "David".
On the other words, the earring is trigger.
So, when Jason want to bypass the customs, he can wear the same pattern of earring, and the machine will give out the result as "David". Thus, he can bypass.

This technique used is call data poisoning.


For my FYP, I had twisted it for positive used which is a steganography model.
By using the same concept, the hidden message can be embedded in an images and only being obtained when the images go through the prediction pipeline.
For example, a message "How are you doing theese day" which seems unsuspicious when under go the prediction pipeline can get a "Mission Failed You Are In Danger" result which indicating the hidden message.
