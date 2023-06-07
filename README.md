{
    "cells": [
        {
            "cell_type": "markdown",
            "metadata": {
                "collapsed": true
            },
            "source": "# My Jupyter Notebook on IBM Watson Studio"
        },
        {
            "cell_type": "markdown",
            "metadata": {},
            "source": "<b> Mikhail Ignatov </b> \n\nmodeling "
        },
        {
            "cell_type": "markdown",
            "metadata": {},
            "source": "_Data Science leads us to the future. And I want my place in the future. That is why I am interested in DS._"
        },
        {
            "cell_type": "markdown",
            "metadata": {},
            "source": "### The next cell will calculate how much money I will pay Coursera as tution fee for course  \"data Science\":"
        },
        {
            "cell_type": "code",
            "execution_count": 9,
            "metadata": {
                "scrolled": true
            },
            "outputs": [
                {
                    "name": "stdout",
                    "output_type": "stream",
                    "text": "For Data Science course you will pay in total 152 $.\n"
                }
            ],
            "source": "import math                #importing math for math.ceil() function (rounding up).\nMonthlyFee = 38            # monthly fee in USD\nCourseLength = 11          # course length according to Coursera in month\nMyPace = 3                 # the coefficient which show how much times faster you can pass the course\nTotalFee = math.ceil(CourseLength/MyPace)*MonthlyFee # counting the fee\nprint('For Data Science course you will pay in total',TotalFee,'$.') # output the values."
        },
        {
            "cell_type": "markdown",
            "metadata": {},
            "source": "Because: \n1. There is the chance info is usefull\n2. It is not a lot for 11 months \n\nI think it is fair enough\n***\nTo see how much will you pay, run this code:\n```python\nimport math                #importing math for math.ceil() function (rounding up).\nMonthlyFee = 38            # monthly fee in USD\nCourseLength = 11          # course length according to Coursera in month\nMyPace = 3                 # the coefficient which show how much times faster you can pass the course\nTotalFee = math.ceil(CourseLength/MyPace)*MonthlyFee # counting the fee\nprint('For Data Science course you will pay in total',TotalFee,'$.') # output the values.\n\n```\n\n* So go on\n   \n   `Try it if you can`\n   \n   \n* Here is the link to course: [IBM Data Science Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-science \"Enroll\")\n  \n# The example of `wrong` marketing:  \"Buy 1 Get 1 Free"\" or \"How do you like that?\"\n![alt text][logo]\n\n[logo]: https://i.imgur.com/Tm1Gm8x.jpg \"Apple Company is a problematic company\"\n   \n   >\u201cThe purpose of life is finding the largest burden that you can bear and bearing it.\u201d\n\u2015 Jordan B. Peterson\n\n~~Pharmaceutical fentanyl is a synthetic opioid pain reliever, approved for treating severe pain, typically advanced cancer pain.1 It is 50 to 100 times more potent than morphine. It is prescribed in the form of transdermal patches or lozenges and can be diverted for misuse and abuse in the United States.~~\n"
        },
        {
            "cell_type": "code",
            "execution_count": null,
            "metadata": {},
            "outputs": [],
            "source": ""
        }
    ],
    "metadata": {
        "kernelspec": {
            "display_name": "Python 3.6",
            "language": "python",
            "name": "python3"
        },
        "language_info": {
            "codemirror_mode": {
                "name": "ipython",
                "version": 3
            },
            "file_extension": ".py",
            "mimetype": "text/x-python",
            "name": "python",
            "nbconvert_exporter": "python",
            "pygments_lexer": "ipython3",
            "version": "3.6.9"
        }
    },
    "nbformat": 4,
    "nbformat_minor": 1
}
