//////Today is the second day of Code 201.

 so far the headaches of studying prior to this class have helped me a ton.

So far HTML is easier then JavaScript because I'm not drawing elipses and trying to make a triangle fit. Yet, its starting to piss me off with how much information I am absorbing that is refusing
to correlate with each other.I thought it was cool to see how a webpage is structured so I can see why it is important to keep the code clean.
I hope to understand coding as well as I understood electrical troubleshooting and repair on the CH-53E helicopter.

I also found out that using Windows for this course is a pain in the ass. Other than that I like that the instructor actually cares about our success
and I'm pretty sure he plays League of Legends since he named his cat "Alistair".


///////////////////// DAY 5
wooo Its friday on the first week! so far ive felt a rollercoaster of emotions. I originally thought I bit off more than I could
chew but after the 2nd lab I felt better.  Going home accomplished of that number 6 question was a feeling of accomplishment
I haven't felt in years.  It was like fixing the aircraft and watching it fly off thanks to me. I didn't expect to
find out that paired coding was way more fun.  I mean ya its wonderful to bust my ass and see my achievements, but its
another to see what 2 minds can do in a smaller amount of time.  At the beginning of this week I was forcing myself to
open the laptop at home after a long commute, but yesterday I found myself willingly sitting down and cracking open the
books.  I can't wait until next month when I visit my homies in San Diego and make them think im all over the yahoo news
for "being able to drink longer then Mike" (a buddy of mine).  
What I really can't wait for is applying all this new stuff to a job and paying off all my families' bills so we can finally
bounce back from the recession all those years ago.



//////////////////////////////
7/17/2017
week 2-----Monday

Today we went over how to geneerate a random number and use it for a "Salmon Cookies" inventory list.
All of us were fairly struggling with it and trying our best to help each other.  it looked like this.

//////////////////////        Alki          ////////////////////
<!-- var alki= {
  minCust: 2,
  maxCust: 16,
  avgCook: 4.6,
  hourC: [],
  randomPeeps: function (min,max){
    return Math.floor(Math.random() * (this.maxCust - this.minCust)) + this.minCust
  },
  cookiesPerHour: function(){
    for(var i = 0; i < timeOfDay.length; i++){
      var cookiesPer = Math.floor(this.avgCook * this.randomPeeps());
      this.hourC.push(cookiesPer);
    }
    return this.hourC;
  },
  cookiesPD: function(){
    var total = 0
    for(var i = 0; i < this.hourC.length; i++){
      total += this.hourC[i];
    }
    return total;
  },
  render: function(){
    var alkiUl = document.getElementById('alki');
    for(var i = 0; i < timeOfDay.length; i++) {
      var liEl = document.createElement('li');
      liEl.textContent = timeOfDay[i] + ': ' + this.hourC[i] + ' Cookies per hour';
      alkiUl.appendChild(liEl);
    }
    var total = document.getElementById('alki');
    var liEl = document.createElement('li');
    liEl.textContent = 'total: ' + this.cookiesPD(total);
    total.appendChild(liEl);
  }

};

alki.randomPeeps();
alki.cookiesPerHour();
alki.render(); -->

// ++++++++++++++++++++++++++
very fun and very interesting to see it finally working together.  Its crazy how we're using multiple functions as local
variables and having it work with itself multiple times.  Im starting to realize that I can literally do whatever
I want.  However its intimidating to even start and we do get help from the TA's.  I got this.


/////////++++++++++++++++++++++++
I learned how to create a grid with the locations and math of random cookies sold.  With guidance from Mark
I was able to understand how to add the total to the equation.  I need to study a lot more so i can actually
retain all the information.  I have all the codes saved and need to go over them this weekend.
