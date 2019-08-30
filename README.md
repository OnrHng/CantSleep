# CantSleep
count sheep

TASK

If you can't sleep, just count sheep!!

Task:
Given a non-negative integer, 3 for example, return a string with a murmur: "1 sheep...2 sheep...3 sheep...". Input will always be valid, i.e. no negative integers.

    var countSheep = function (num){
      var mirmir = "";
      for (i = 1 ; i < num ; i++) 
        {
        mirmir += i + ' sheep....' ;
      }
      return mirmir;
    }

    countSheep(22);


best
