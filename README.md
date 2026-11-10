# Common Cortex

Open-source AI raised by the people who run it. The project is Common Cortex; the shared model is the Cortex. Status: pre-alpha, no code released.

## Basic features

- Local chat with the Cortex on your own machine. Private, works offline.
- Background trainer: your PC trains your fork of the Cortex in the background, inside limits you set, and steps aside when you are using the machine.
- Forks: your personal version of the Cortex, stored as a small add-on file, trained on a diet you choose.
- The Pool: where forks are submitted for checking.
- The Exam: a fixed automated test every submitted fork must pass.
- Verification quests: small human-judgment games (for example, pick the better of two answers) that check what the Exam cannot. They also check the checkers.
- Merges: verified forks combine into the next Cortex release, which everyone downloads and forks again.
- World view: a live view of the model's inner state while it trains.
- Phones: chat and quests only. No training.
- All data, chats, and logs are stored on your own machine as ordinary files. There is no central server holding them.

## Data rules

- The Cortex learns only from what people deliberately submit or donate, plus public-domain works.
- Nothing is scraped. Nothing is taken.
- No other AI model is used as a base or a teacher.
- Every piece of training data is labelled with where it came from.
- Using your chats for training is opt-in, off by default.

## Roadmap

1. Spark: a tiny from-scratch model, a trainer, and local chat, on one PC.
2. The Exam (v0) and the fork submission format.
3. The full loop on one PC: forks, Pool, Exam, merges, family tree.
4. World view and the first verification quest.
5. A second PC joins the loop; human quests become the merge gate.

## Proof bar

Nothing beyond this document is published until all of these are true:

- The model visibly learns.
- Forks trained on different diets diverge measurably.
- A merged model beats both of its parents on the Exam.
- A deliberately poisoned fork is rejected without help.
- A newcomer can run the whole loop from the README alone.
