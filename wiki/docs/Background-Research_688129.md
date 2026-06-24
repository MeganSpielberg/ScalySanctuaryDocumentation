# Background Research

> ℹ️ **Note:** Author: Megan and Valentino

### 🎲 The Project

Scaly Sanctuary is a digital reptile caretaking game developed as part
of the Master of Applied IT program at Fontys University of Applied
Sciences. The project explores how specific design decisions in
interactive systems influence learning outcomes and user engagement.
Digital learning environments increasingly integrate game mechanics and
interactive agents to enhance user experience. However, it remains
unclear whether improved learning outcomes stem from the presence of
game structure (e.g., goals, progression, feedback) or from increased
interactivity and responsiveness of virtual entities. This project
investigates these factors within the domain of reptile caretaking
education. Reptile welfare is often misunderstood in informal
educational contexts, and digital simulations may provide a scalable and
engaging method for introducing foundational knowledge. The Scaly
Sanctuary prototype serves as an experimental platform to systematically
manipulate design variables and measure their effects on knowledge gain
and engagement.

### 💡 Conceptual Foundations of Game-Based Learning

Game-Based Learning (GBL) broadly refers to instructional activities
that use games to achieve educational objectives (Talan et al., 2020).
Unlike entertainment games, educational games are intentionally designed
to support both intrinsic and extrinsic motivation while promoting
structured knowledge acquisition (Plass et al., 2015).

#### 🎮 GBL vs. Gamification

Gamification differs conceptually from GBL. While GBL changes the
learning experience through gameplay itself, gamification incorporates
game elements such as:

- points,

- badges,

- leaderboards,

- rewards,

- and progression systems

into otherwise traditional educational structures (Nadolny et al.,
2017).

#### 🗂️ Categories within Game-Based Learning

Several overlapping categories exist within this field:

| Category | Description |
|----|----|
| *Serious Games* | Games designed to train specific skills in realistic contexts |
| *Serious Educational Games* | Pedagogically driven immersive virtual learning environments |
| *Simulations* | Systems that replicate real-world activities for safe, repeatable practice |

(Lamb et al., 2018)

> ℹ️ **Note:** Research consistently suggests that meaningful educational impact
> depends on intentional instructional design rather than entertainment
> value alone.

### 🎮 Casual Gaming

Casual games are mainly defined by their accessibility, simple
mechanics, and flexible time commitment rather than by a single feature.
Multiple sources agree on core characteristics. **Gajadhar et al. 2010**
and **Reis 2013** identify easy access, simple rules, and simple
interfaces as defining traits. **Johnson 2018** lists six design traits:
appealing themes, ease of access, ease of learning, minimal required
expertise, fast rewards, and temporal flexibility. **Juul 2012**, a book
on the history and design of casual games, argues that casual games are
designed to fit into players’ lives through quick play sessions, rather
than forcing players to change their schedules. Evidence also shows that
the definition is complex. **Kuittinen et al. 2007** notes that “casual”
is ambiguous. It can describe the player, the game, the playing style,
business models, or accessibility. This can cause confusion. **Chess
2020** describes “casual game” as an industry catch-all term, often used
dismissively and covering Match-3, puzzle, and hidden object games. The
literature suggests that casual games focus on low barriers to entry and
flexible engagement, rather than on complexity or long-term demands.
Casual games may reduce stress and improve mood, but evidence for
cognitive benefits is limited. The strongest evidence relates to mental
health. **Pine et al. 2020** conducted a systematic review of 13 studies
on casual games’ effects on anxiety, depression, stress, and low mood
and found “promising effects.” **Stanhope, Owens, and Elliott 2015**
reported that casual gaming improved positive mood more than guided
relaxation in a sample of 65 participants. However, **Squire et al.
2023** found “little support for the cognitive benefits of playing
casual games, except for the elderly or those with dementia,” although
they did find social and emotional benefits when games are “played
mindfully, and within robust social contexts.”

### 🧠 Psychological and Cognitive Effects

Taken together, this body of research draws a clear line: casual games
show consistent value for mood and stress regulation, but the evidence
for broader cognitive enhancement is thin outside of older or
cognitively vulnerable populations. This distinction is important for
Scaly Sanctuary, which aims not only to entertain but also to facilitate
measurable educational outcomes.

### 🎓 Serious Games

Educational content in games is usually delivered in four main ways:
integration into game mechanics, narrative or storytelling, text-based
content, and scaffolding structures. Findings on these methods are mixed
but generally positive.

| Study | Findings | Reference |
|----|----|----|
| Text-based instruction vs. game mechanics | Game mechanics were statistically better for one learning objective but showed no significant difference for others. | Molnar and Kostkova 2013 |
| Interactive digital narratives | Can integrate learning objectives effectively through puzzle sequences. | Molnar and Kostkova 2015 |
| Targeted content scaffolds | Significantly improve learning performance. | Tsai et al. 2011 |
| Integrated game-mechanics approaches | More motivating and more educationally effective than extrinsic reward models. | Habgood, Ainsworth, and Benford 2005 |
| Effective integration of content | Requires embedding content in core gameplay rather than “superimposing” it. | Fisch 2005 and Bellotti et al. 2009 |
| Traditional instructional objectives and storytelling-based approaches | Can work together instead of being in conflict. | Mill, Ribeiro, and Veloso 2023 |

### 🕹️ Games vs Simulations

> ℹ️ **Note:** Research suggests that games always include clear objectives and
> measurable outcomes. The National Research Council states that games
> contain goals, rules, feedback systems, and structured challenges
> (National Research Council 2011). Players can win, lose, or track their
> progress. Feedback helps them adjust their actions.

Games and simulations differ mainly in purpose. Narayanasamy et al. 2006
argues that games are built around victory conditions and artificial
challenges. Simulators aim to reproduce real-world systems as accurately
as possible. In simulations, the focus is on realism and correct task
performance, not winning. This difference also appears in education.
Educational games use structured goals and competition to support
learning. Educational simulations focus on modeling real systems so
learners can see how they work. Vlachopoulos and Makri 2017 note that
simulations emphasize fidelity and experiential understanding rather
than game-based success.

### 🤝 Interactivity in Games

Interactivity in games is generally understood as the requirement for
active engagement from an external agent (the player) for the game to
function. Unlike passive media, games gate their content behind
challenges, such as manual skills or puzzles, that require significant
player action to progress (Smethurst and Craps 2014). This creates a
feedback loop where the game reacts to player input and the player, in
turn, modifies their strategy in response to the game’s state; some
scholars call this hybrid process “interreactivity” (Smethurst and Craps
2014; Stang 2019).

#### 🎛️ Levels of Interactivity

- On-line Engagement: This represents high levels of interactivity where
  the player is in direct control of the action and is taking
  significant actions within the game world.

- Off-line Engagement: This occurs when the player is still attentive
  but in a passive way, unable to influence the game state. Examples
  include unskippable cutscenes, loading screens, or periods of
  “relative calm” in which characters serve as anchors for empathy
  rather than tools for action.

- Intermediate States: Some moments, like quick-time events, allow for
  limited, scripted intervention during cutscenes through predetermined
  button presses, representing a middle ground on the interactivity
  scale.

#### ↔️ Interactive vs. Non-Interactive Entertainment

The primary difference lies in whether the “audience” is an observer or
a participant.

| Feature | Non-Interactive (e.g., Film/Books) | Interactive (Games) |
|----|----|----|
| *Status* | Fixed and self-contained; complete even without an audience. | *Incomplete construct*; requires player input to function and become a full experience. |
| *Role* | The audience observes and interprets but cannot influence the outcome. | The player is a *vital catalyst* who influences the game state and outcome. |
| *Control* | The author has full control over structure, pace, and characters. | The author controls the rules and “narrative shell,” but the player controls *progress and perception*. |
| *Emotions* | Evokes indirect, reactive emotions for characters. | Can evoke *direct personal emotions* like guilt, regret, and personal satisfaction. |

(Backer 2011; Smethurst and Craps 2014)

### 📈 Measuring Engagement

Measuring engagement in games is a multidimensional process. It uses
both behavioral metrics and self-report methods to create a “ground
truth” for player experience (Rashed et al. 2025).

#### 📊 Behavioral Metrics

Industry metrics offer practical insights into engagement patterns and
business impact (Rashed et al. 2025). Common Key Performance Indicators
(KPIs) include Daily Active Users (DAU), Monthly Active Users (MAU), and
retention rates. These measure how many players return to a game after
specific time periods (Hubka 2024). In modern player modeling,
especially in free-to-play games, developers also track monetization and
churn prediction to see whether players will stay engaged or stop
playing (Mikkelsen, Holmg˚ard, and Togelius 2017).

Behavioral data also includes “endurability,” which is a player’s
long-term commitment, return behavior, and replayability. These metrics
are usually collected via game telemetry, which logs detailed user
inputs and interactions to build a data structure of player skill and
experience. These methods are non-intrusive and allow large-scale data
collection, but they may oversimplify engagement by focusing mostly on
goal-directed behavior (Rashed et al. 2025).

#### 📋 Self-Report Methods

Researchers use self-report methods to validate engagement levels and to
capture players’ internal states. A common tool is the Game Engagement
Questionnaire (GEQ) (Brockmyer et al., 2009), which measures reliability
and dimensionality during gameplay (Rashed et al. 2025).

> ℹ️ **Note:** Other well-known tools include the Flow Questionnaire (Csikszentmihalyi,
> 1998), the 4 Presence Questionnaire (Witmer and Singer, 1998), and the
> Immersive Experience Questionnaire (IEQ) (Jennett et al., 2008). These
> instruments measure constructs such as absorption, sensory factors, and
> empathy (Reichart 2018).

### 💡 Measuring Learning Effect

Measuring the learning effect of a serious game is a multi-dimensional
process that involves evaluating academic achievement, behavioral
changes, and engagement levels. Because serious games are designed for
educational rather than purely entertaining purposes, their evaluation
must demonstrate that the intended learning has actually happened
(Bakkali Yedri, Lotfi, and Bouhorma 2018; Zhonggen 2019). These are the
primary ways to measure the learning effect of a serious game:

#### 📊 Core Quantitative Methods

The most common way to empirically measure learning gains is through a
quasi-experimental design involving a control group and an experimental
group (Diaz and López 2024).

| Method | Description |
|----|----|
| Pre-tests and Post-tests | These are typically administered at the beginning and the end of the gaming experience to determine the progression of student learning (Bakkali Yedri, Lotfi, and Bouhorma 2018; Din, Baig, and Khan 2023). |
| Effect Size Calculation | Researchers often use statistics like Hedges’ g or Cohen’s d to determine the magnitude of the learning impact. For instance, a value of 0.8 is generally considered a large effect size, while 0.5 is medium (Diaz and López 2024). |
| Standardized Achievement Tests | Comparing game results against national or state standards (such as the NAEP) can provide a benchmark for how the game impacts proficiency in subjects like mathematics or science (Conmy 2023). |

#### 📋 Integrated Assessment Types

Effective measurement often combines several types of assessment to
capture the full learning timeline (Bakkali Yedri, Lotfi, and Bouhorma
2018):

| Assessment Type | Description |
|----|----|
| Diagnostic Assessment | Used before the game starts to assess the learner’s baseline knowledge. |
| Formative Assessment | This occurs during the game and provides immediate feedback to the learner. It allows for adjustments in real-time and supports the learning process through prompts or ”NPC” guidance. |
| Summative Assessment | This measures the learner’s final achievements at the end of the experience through exams, final scores, or portfolios. |
| Integrative/Authentic Assessment | Evaluates how well a student can link scientific knowledge to real-world actions or policy. |

(Bakkali Yedri, Lotfi, and Bouhorma 2018)

#### 🎮 In-Game Data and Learning Analytics

Modern serious games use learning analytics to track user behavior
without needing external questionnaires.

Real-time evaluation is used to diagnose issues throughout the game
scenario, calculating scores based on specific indicators such as the
time taken between identifying a problem and resolving it. (Bakkali
Yedri, Lotfi, and Bouhorma 2018).

| Metric | Details |
|----|----|
| Specific Metrics | Score and number of right/wrong answers. |
| Time spent | Participating in specific activities or levels. |
| Redundant faults | Making the same error multiple times, which can indicate areas of difficulty. |
| Knowledge retention | Measuring concepts remembered over a longer period after the game has concluded. |

(Bakkali Yedri, Lotfi, and Bouhorma 2018; Diaz and López 2024; Conmy
2023)

#### 🖼️ Structured Frameworks

To ensure a robust measurement, experts suggest using established
frameworks to map pedagogy to gameplay:

| Framework | Description |
|----|----|
| LM-GM Framework | This maps Learning Mechanics (e.g., repetition, reflection) to Game Mechanics (e.g., levels, rewards) to ensure the game features directly support the pedagogical goals (Lim et al. 2013). |
| AvaliaJS Model | A conceptual guide that helps teams plan the design and execution of student performance assessments in serious games (Oliveira, Rocha, and Goya 2021). |
| F4ASG | A framework specifically for adaptive serious games that focuses on how game elements can be changed to optimize learning outcomes and knowledge transfer (Pistono et al. 2024). |

### 🐶 Understanding Pet Behavior

Pet behavior is best understood through direct observation of the
animal’s usual patterns. These include body posture, vocalizations,
activity levels, and changes from baseline. The literature highlights
observation as the main method. Riccomini 2009 advises pet owners to
“watch and listen to their pets” to understand behavior. Boyce, Zingg,
and Lightfoot 2001 gives concrete examples for ferrets and recommends
that owners note “sudden changes in activity levels, food/water intake,
routine behaviors performed out of context, and changes in personality
or attitude.” Frank 2014 states that “disease is always associated with
changes in behavior such as disappearance of normal behaviors or
appearance of new behaviors.” For dogs, Hsu and Serpell 2003 created a
validated 68-item questionnaire that measures responses to specific
events and situations in the pet’s usual environment. This tool is more
formal than typical owner observation.

#### 📚 Learning material for pet caretaking

People learn to care for pets, particularly reptiles, through a
combination of professional consultation, digital communities, the pet
industry, and public health campaigns. While traditional pet owners
(dogs and cats) rely heavily on veterinarians (utilized by 67% of
owners) and groomers, the learning process for reptile keepers often
involves specialized behaviorists and enthusiasts (TGM Research 2023;
Azevedo et al. 2021).

#### 💼 Professional and Scientific Guidance

For many, the learning process begins with animal behaviorists,
trainers, and consultants who provide education to align owner
expectations with the natural history and biological needs of the animal
(Torrini 2025). Professionals help owners understand:

- Species selection: Choosing a reptile whose temperament and space
  needs match the owner’s lifestyle.

- Environmental management: Learning how to provide essential husbandry
  like temperature gradients, UVB lighting, and adequate space for full
  body elongation.

- Behavioral interpretation: Distinguishing between normal behaviors
  (like basking) and stress-related behaviors (like repeatedly hitting
  the glass).

- Advanced training: Using positive reinforcement and cooperative care
  to reduce stress during handling and veterinary visits.

(Azevedo et al. 2021; Torrini 2025)

#### 💬 Digital Communities and Social Media

Social media has become a primary hub for learning. Enthusiasts often
join dedicated reptile groups on platforms like Facebook and Patreon to
share experiences and receive advice from more experienced keepers.
These forums allow for the rapid exchange of information, though some
sources note that owners may still rely on ”folklore” knowledge rather
than peer-reviewed science (Azevedo et al. 2021; Torrini 2025).

#### 🛍️ The Pet Industry and Retailers

Many owners receive their initial care instructions from pet shops: one
survey found that 65% of reptile owners had purchased their animal from
a pet shop (Azevedo et al. 2021). However, there is a noted
challenge where the exotic pet industry may promote reptiles as
”low-maintenance” pets, which can lead to a gap between an owner’s
perceived knowledge and their actual ability to meet the animal’s
complex needs (Azevedo et al. 2021).

#### 🏥 Public Health and Educational Campaigns

Education is also driven by the need to manage health risks.
Veterinarians and public health bodies play an important role in
teaching owners about risks, such as the transmission of Salmonella
(Corrente et al. 2017). Learning in this area focuses on:

- Hygiene practices: The importance of handwashing after handling
  animals or cleaning habitats.

- Habitat maintenance: Ensuring drinking water is replaced regularly to
  prevent infection.

- Responsible sourcing: Understanding the difference between
  captive-bred and wild-caught animals is a high priority for many
  enthusiasts.

(Azevedo et al. 2021; Corrente et al. 2017)

Despite these resources, studies indicate that many reptile owners still
struggle to meet all essential husbandry needs, even when they feel they
have a good understanding of their pet’s behavior (Azevedo et al. 2021).
This highlights a continuing need for science-based education that
bridges the gap between basic survival and optimal animal welfare
(Azevedo et al. 2021; Torrini 2025).

## 🤖 AI in Veterinary and Educational Contexts

Recent developments in AI have rapidly expanded veterinary technology
capabilities.

### 🧰 Modern Veterinary AI Tools

Modern veterinary AI tools include:

| Category | Examples |
|------------------------------|--------------------------------|
| Digital Medical Scribes      | ScribbleVet                    |
| Symptom Triage Systems       | Petriage                       |
| Automated Diagnostic Support | Vet-AI, Zoetis Vetscan Imagyst |
| Educational Chatbots         | CoVet, CatGPT, VetClinPathGPT  |
| Client Communication Systems | PetBERT                        |

These systems support:

- SOAP note generation (SOAP = Subjective, Objective, Assessment, Plan —
  the standard structure vets use to write up a patient visit),

- ICD-11 coding (tagging a diagnosis with its code from the WHO's
  International Classification of Diseases, 11th edition, so cases can
  be tracked and compared consistently),

- diagnostic imaging,

- symptom triage,

- educational guidance,

- and workflow automation.

> ℹ️ **Note:** Educational AI chatbots are particularly relevant for Scaly Sanctuary
> because they demonstrate how conversational agents can support:
> - inquiry-based learning,
> - clarification,
> - explanation,
> - and contextual guidance.

### 🎮 Educational Game Framework with an AI Veterinarian

The combined literature on Game-Based Learning and veterinary AI
suggests a strong foundation for an educational reptile caretaking game
featuring an embedded AI veterinarian.

The proposed gameplay loop focuses on three core activities:

- feeding the reptile,

- cleaning and maintaining the terrarium,

- physically interacting with the reptile appropriately.

Each action influences:

- reptile health,

- stress levels,

- visible behavior,

- and environmental conditions.

The educational depth emerges not from mechanical complexity but from
understanding *why* certain caretaking actions are correct or incorrect.

#### 🩺 Role of the AI Veterinarian

Within the game, the AI veterinarian acts as an interactive knowledge
companion rather than a diagnostic simulator.

Players can consult the AI regarding:

- feeding schedules,

- habitat conditions,

- stress behaviors,

- hygiene,

- lighting,

- or species-specific care.

Importantly, the AI does not simply provide direct answers. Instead, it
encourages reflection and inquiry. For example:

```mermaid
flowchart LR
    A[Reptile becomes lethargic] --> B[Player consults the AI vet]
    B --> C[AI explains possible causes]
    C --> D[AI discusses husbandry factors]
    D --> E[Player reaches conceptual understanding]
```

This creates a scaffolded learning experience emphasizing:

- metacognition,

- reflection,

- and inquiry-driven learning.

#### 🔁 Repetition as a Learning Mechanism

The gameplay loop intentionally relies on repetition.

Repeated feeding, cleaning, and observation cycles allow players to:

- test knowledge,

- recognize behavioral patterns,

- observe consequences,

- and refine decision-making.

The AI veterinarian enriches this repetition by contextualizing outcomes
and reinforcing reasoning.

This directly addresses a known limitation of many educational games:
engagement does not automatically guarantee long-term retention.
