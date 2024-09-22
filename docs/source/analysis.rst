.. toctree::
   :maxdepth: 2
   :caption: Contents:



Analysis
================================

.. topic:: **So Which Bot is Better?**

     **With Human as opponent, Minimax bot plays better than RL bot.**

     **In a Checkers game between Minimax bot and RL bots, The RL bot can exhibits perfect play if trained against Minimax bot of that specific depth.**


    When playing against human opponents, our RL bot, falls short due to the extensive training it requires. In contrast, a Minimax bot with a search depth of 3 proves to be a significantly more formidable opponent.


    However when these bots face off against each other, the RL bot's strengths become apparent. If trained against a Minimax bot of a specific depth, the RL bot can consistently defeat it. This is because the RL bot only needs to identify weaknesses in the Minimax bot's decision-making process, which is often constrained by its fixed search depth. Once the RL bot has learned to exploit these weaknesses, it can achieve perfect play against that particular Minimax bot.


    While this training method allows the RL bot to excel against Minimax bots, this approach is not ideal for playing against human opponents. This type of training lead to a static loop, where the RL agent becomes overly reliant on its knowledge of the specific Minimax algorithm it was trained against. This limits its ability to adapt to new or unexpected strategies, hindering its performance against human player.






