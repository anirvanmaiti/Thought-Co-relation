# Thought-Co-relation

Brain Computer Interface, BCI is a direct communication pathway between the brain and
an external device. BCIs are often directed at assisting, augmenting, or repairing human
cognitive or sensory-motor functions. It allows to convey messages to the outside world
from one’s thoughts. EEG is a non-invasive method, which allows to record the electrical
activity of the brain. NeuroSky MindWave device will be used for this purpose. The
NeuroSky device measures the attention level, meditation level and eye-blink strength of
an individual. The acquired EEG signals need to be further filtered and processed.
Every event/task of a human being produces electrical signals in a particular region of the
brain. These patterns lead to waves characterized by different amplitudes and
frequencies:(i) Delta (0.5−4Hz) (ii) Theta (4−8Hz) (iii) Alpha (8−13Hz) (iv) Beta
(13−30Hz) iv) Gamma (> 30Hz)
By studying these patterns of the signals, based on the frequency ranges, we can classify
and analyze the thoughts of the subject. In this project, the data is extracted from the
NeuroSky device for analysis. We will be recording the activity of a few subjects while
they are shopping online, and use this data for predictive analysis to enhance the website
performance.

# Problem Definition

With more India's online shopping registering a phenomenal 100 per cent annual
growth, many retail chains and consumer durable companies are joining the Web
bandwagon to tap the e-shopping market. The online shopping industry in India is fast
catching on, not just in the larger metros but also in the smaller cities. With such a large
market size, companies, right from retail shops to consumer goods, are entering the Web
space to attract potential customers. The customer behavior is changing dramatically.
People are not only using the Web to book air tickets and movie tickets but also do not
hesitate in placing orders for mobiles, laptops and other consumer electronics and home
appliances. In order to make online shopping a smooth and hassle free experience for the
customers, the design of the website is an important factor to be considered.
 In our proposed system, we analyze customers’ reactions as and when they are
shopping in order to improve the website according to their likes and dislikes. To capture
these reactions, we use the NeuroSky Mindwave device. We then study the users’ attention
levels as and when they shop, and observe how the values change while they browse
through the site. We then try to classify users’ actions such as going back to a previous
page, buying and exiting the site and generic actions such as scrolling, applying brand filters
for products etc. By identifying the time at which the user decides to go back to the home
page, the company can alter their site to display other product recommendations which
might interest the customer and prevent them from exiting the site. Identifying the time at
which the user completes his shopping and proceeds to check out, will help the company
to promote other offers and discounts which might encourage the shoppers to return to their
site in the future.

# Proposed System

In our project, we collect the data from the NeuroSky device through a third-party
android application, EEG Analyzer. We receive the data in the form of CSV files through
this particular application. We store these files in our own DropBox folder. The data sets
are then filtered and processed further using RStudio.
 The data sets include the time interval values (in milliseconds) and the corresponding
attention, meditation and eye blink strength values. We then extract the features such as the
different user actions i.e. going back to a previous page and buying and completing a
transaction. Once we identify the features, we then build a classifier model to classify the
features.
 We use certain samples of the data sets for training purpose and the remaining for
testing. The accuracy of the model is determined to verify the classifier model designed.
This classifier model can be proposed to companies for use in order to analyze customer’s
reactions and enhance their website performance.
