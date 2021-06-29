<b> BASIC STRUCTURE OF SLIDING WINDOW TECHNIQUE  </b> 

<ul>         
  <li>  while(j<N)  </li> 
          <li>  { </li> 
           <li>  CONDITION FOR CALCULATION ; </li> 
              <li> if(j-i+1==K) //checking end pt to a particular window </li> 
                <li> { </li> 
                <li>   ANS SAVE TO TILL NOW CALCULATION FOR A GIVEN WINDOW; </li> 
                 <li>  i++ //for new window </li> 
           <li>} </li> 
                 <li>j++; //traversal of array/string  </li> 
        <li>}</li>  </ul>
