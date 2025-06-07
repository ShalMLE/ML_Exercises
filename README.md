Notes
Python
   1. Numbers - Integer , Floating -
   2. Operations - +, -, *, /, %, **
   3. Variable Naming Convention - variable sperated by uderscore like var_of_num
   4. String - '' or " ", print("My Name is {}".format('Shalini')
   5. Data Structures in Python
      5.1 Lists
          [1,2,3],[1,'a',2] # Retain order in order
          mylist[0] #Indexing to fetch element in a list
          mylist[-1]
          mylist[0]='c'#change element in the list or reassign
          mylist.append('d') #add element in a list
          mylist[2][1] # grab elements from a nested list

      5.2 Dictionary or Hashtables in other languages
          d = {'key1':'value1', 'key2': 'value2'} # do not retain any order
          d['key1'] # value1

      5.3 Boolean
          True - 1
          False - 0

      5.4 Tuples
          t = (1,2,3) # Tuples are immutable means cannot reassign elements     already present in the list.
          t[0] = '1' # Type Error
          
      5.5 Sets
          Unordered collection of unique elements.
          {1,2,3}

  6. Operators
     1. Comparison Operator
          - Compare two different variables/numbers/strings
          -  >, <, >=, <=, ==
     2.  Logical Operators
          - Allows to combine multiple comparision operators
          - 10 > 5 and 20 > 12 or 16 < 20
   7. If, elif and Else
        if condn:
            statement
        elif condn:
            statement
        else:
            statement
      
  8. Looping
       for Loop
       while loop

  9. Range function 
     for i in range(5) or range(0,5) or range(0,10,2)

  10. List Comprehension
      X = [1,2,3,4,5]
      y = []
      for num in X:
        y.append(num ** 2)

            OR
        y = [num**2 for num in x]

  11. Function/ custom Function
      def my_func(name='Nomane'):
      #docsting
        '''
          This printout out user name!
        '''
        print('Hello'+name)

      my_func('Shal')

  12. def times_two(var):
        return var*2
      times_two(10)

      OR

      lambda var: var*2 #anonymous function

  13. Built-in methods for strings
      lower()
      upper()
      split()
      d.keys()
      d.items()
      mylist.pop() #remove last element
      mylist.pop(0) #remove first element
      'x' in [1,2,3]
          
