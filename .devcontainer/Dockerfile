# Copyright © 2001 by the Rectors and Visitors of the University of Virginia. 

# Extend Ubunto 20.04
FROM docker.io/kevinsullivan/leanvm 

# Your extensions to your environment can go here.
# Then you must rebuild the container. You probably
# don't need to do anything here at all, but if you
# find a great improvement to the environment, or a
# bug fix, please send a pull request to upstreeam.
# If you don't know what that means, no worries, you
# can just ignore it.

#RUN \
#    pip install --upgrade pip

RUN pip install beautifulsoup4 &&\
    pip install requests &&\
    pip install pandas &&\ 
    python3 -m pip install --user jupyter sympy nose &&\
    pip install seaborn ipython &&\
    python3 -m pip install -U matplotlib &&\
    pip install scikit-learn &&\
    pip install RISE &&\
    pip install gekko &&\
    pip install keras &&\
    pip install numpy &&\
    pip install plotly &&\
    pip install torch &&\
    pip install statsmodels &&\
    pip install tensorflow &&\
    pip install xgboost &&\
    pip install gensim