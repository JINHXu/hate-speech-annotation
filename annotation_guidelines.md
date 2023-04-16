# Annotating Hate Speech in \#china Tweets

## Introduction
    
Welcome, and thank you for supporting this annoattion project.

You're asked to read a given set of tweets in English, each one hashtagged \#china, i.e. with china-related issues as the main topic. For each tweet, we ask you to determine whether Hate Speech is present (label 1) or not (label 0).

> Hate Speech is commonly defined as any communication that disparages a person or a group on the basis of some characteristic such as race, color, ethnicity, gender, sexual orientation nationality, religion, or other characteristics ([Basile et al., SemEval 2019](https://aclanthology.org/S19-2007/)).

More specifically, according to [Basile et al., SemEval 2019](https://aclanthology.org/S19-2007/) HS may include:

- dehumanization or association with animals or entities considered inferior

- references to certain backgrounds/ethnicities as a threat to the national security or welfare or as competitors in the distribution of government resources

- delegitimation of social position or credibility based on origin/ethnicity 

- insults, threats, denigrating or hateful expressions 

- incitement to hatred, violence or violation of rights to individuals or groups perceived as different for somatic traits (e.g. skin color), origin, cultural traits, language, etc.

- presumed association of origin/ethnicity with cognitive abilities, propensity to crime, laziness or other vices

- references to the alleged inferiority (or superiority) of some ethnic groups with respect to others


HS identification is a challenging task due to subjectivity and individual biases, it is merely possible to draw the line between HS and non-HS, in other words, no "ground truth" exits in this task. Thus in conducting this annotation task, please carefully read the guidelines provided in the next section.


Guidelines
   =

Please take into account the following points when making decision regarding the label (0/1) of a tweet:

1. with \#china being a complex concept, we primarily consider Hate Speech against any China-related aspects, such as the following

    - China the country
    - the Chinese population (domestic/abroad)
        - domestic population residing in China
        - Chinese immigrants to other countries
        - non-permanent Chinese residents to other countries (tourists/students/workers/expatriate etc.)
    - A specific Chinese person (non-political figure)/a group of Chinese persons 

2. Due to the way data was collected and filtered, __HS against non-China-related targets will be rare cases, and will be considered non-HS (label 0)__

3. a message that spreads, incites, promotes or justifies HATRED OR VIOLENCE TOWARDS THE TARGET, or a message that aims at dehumanizing, hurting or intimidating the target

4. feel free to run through the checklist above in the INTRODUCTION section to determine the label


Here a list of other aspects that should be labbeled 0 in our study:

- the rare cases of HS against a non-China-related target

- generic offensive language

- fake news or untrue information

- offense towards political figures

- blasphemy

- historical denial

- overt incitement to terrorism

- defamation


## Examples
   

- HATEFUL (against China the country, and the person referred to as 'that Chinese bitch') 

This bullshit has gone on long enough !
__That Chinese bitch__ lives in luxury !
Fuck the extradition, prisoner swap now &amp; close the door on Chinese 5g we don't want it ! __Fuck Off #China__ !!!
https://t.co/Okg2UCqnP2

- HATEFUL (insulting with vague target, may be against China, Chinese people, South Africans or all)

Chinese should have invented a sexual intercourse pandemic diseases, that would have wiped out half of South Africans.

#Lockdown #Chinese #China __#ChineseVirusCorona__ #epidemic

- HATEFUL (contains explicit hateful hashtag)

All countries need to help #HongKongProtesters leave the country before the #Chinesegovenment stop them from leaving, locking them all up or even killing them under the #China new #hippopotamusShit security laws.

#FreeHongKong

#HumanRights

__\#FuckChina__

- HATEFUL (insulting the country in general)

Hey #china . Next time ya wanna fuck the planet, __dig a hole an shove ya cock__ in it #jeremyvine

- HATEFUL (contains typical racist slur against Chinese people)

If you use one of these, the __chinks__ own you.
#China #Chinese https://t.co/jWyUD0wNt3

- HATEFUL presume a country to crime ("get everyone killed")

Close your FOOD Markets China!! __You are going to get us all killed!!__ &gt;:( #China #ChinaCoronaVirus I do not want spider on my rat brain today!! CLOSE THEM!!! And stop killing cats and dogs too! #ChinaLiedPeopleDied https://t.co/lkqCQ3ATRe



- NOT HATEFUL tweet:

1. It does not incite hatred (fake but not hateful):  

So Sad ! China Evicts Africans from their Homes Claiming they are Importing Coronavirus into China @MaziNnamdiKanu #China where did Corona virus originated? #China show the world proof of your claim. I say #Notoracist #Free the blacks https://t.co/1XNolmzvdb 

2. It does not incite hatred: 

May god spare all of us from these hidden Monsters🙏🏼

They are their half way to end humanity.

#China #COVIDIDIOTS #COVID
#Hantavirus

3. It does not incite hatred

#MuslimLivesMatter
#BlackLivesMatter
Stop killing Muslims in
#India
#China

4. Sarcastic but it does not incide hatred 

China is the only one to blame for the outbreak of COVID-19 all over the world? Look at how America responded to COVID-19. Stop the black brothers from breathing? Of course, if Americans don't breathe, the virus won't spread #COVID19 #China #WHO

5. defamation but not hate

#ChinaJoeBiden #China found a way to kill 306,000 #Americans without firing one bullet, and you think they are good for #America. So good you let #HunterBiden get rich off them. #Treason I say! #StopTheSteaI #StopTheSaleOfAmericaToChina #DemocratsAreCorrupt

### Reference

Valerio Basile, Cristina Bosco, Elisabetta Fersini, Debora Nozza, Viviana Patti, Francisco Manuel Rangel Pardo, Paolo Rosso, and Manuela Sanguinetti. 2019. SemEval-2019 Task 5: Multilingual Detection of Hate Speech Against Immigrants and Women in Twitter. In Proceedings of the 13th International Workshop on Semantic Evaluation, pages 54–63, Minneapolis, Minnesota, USA. Association for Computational Linguistics.
