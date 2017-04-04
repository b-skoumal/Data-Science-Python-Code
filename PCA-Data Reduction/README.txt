Data Source:

"Raw data from online personality tests" http://personality-testing.info/_rawdata/

Answers to the Big Five Personality Test, 
constructed with items from the International Personality Item Pool.

Description:
50 likert rated statements, gender, age, race, native language, country

n = 19719



Download link for zipped folder with CSV: http://personality-testing.info/_rawdata/BIG5.zip

I 

renamed the file to "big5.csv" 



Data cleaning:
- 1 case had 0 (missing) on all personality variables, so that case was deleted. 

(1 of 19,719)
- Cases with ages above 80 were deleted 

(87 of 19,719)
- Cases with invalid country codes were deleted. 

(377 of 19,719)
- Any remaining cases with missing values on demographics variables were deleted
- 


b5.csv contains only the 50 Big 5 variables

Collected from a personality test:

Where 1=Disagree, 3=Neutral, 5=Agree (0=missed). 

All were presented on one page in the order E1, N2, A1, C1, O1, E2...... 

E1	I am the life of the party.
E2	I don't talk a lot.
E3	I feel comfortable around people.
E4	I keep in the background.
E5	I start conversations.
E6	I have little to say.
E7	I talk to a lot of different people at parties.
E8	I don't like to draw attention to myself.
E9	I don't mind being the center of attention.
E10	I am quiet around strangers.
N1	I get stressed out easily.
N2	I am relaxed most of the time.
N3	I worry about things.
N4	I seldom feel blue.
N5	I am easily disturbed.
N6	I get upset easily.
N7	I change my mood a lot.
N8	I have frequent mood swings.
N9	I get irritated easily.
N10	I often feel blue.
A1	I feel little concern for others.
A2	I am interested in people.
A3	I insult people.
A4	I sympathize with others' feelings.
A5	I am not interested in other people's problems.
A6	I have a soft heart.
A7	I am not really interested in others.
A8	I take time out for others.
A9	I feel others' emotions.
A10	I make people feel at ease.
C1	I am always prepared.
C2	I leave my belongings around.
C3	I pay attention to details.
C4	I make a mess of things.
C5	I get chores done right away.
C6	I often forget to put things back in their proper place.
C7	I like order.
C8	I shirk my duties.
C9	I follow a schedule.
C10	I am exacting in my work.
O1	I have a rich vocabulary.
O2	I have difficulty understanding abstract ideas.
O3	I have a vivid imagination.
O4	I am not interested in abstract ideas.
O5	I have excellent ideas.
O6	I do not have a good imagination.
O7	I am quick to understand things.
O8	I use difficult words.
O9	I spend time reflecting on things.
O10	I am full of ideas.