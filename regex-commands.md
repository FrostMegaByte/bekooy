## TODO:
- (Schepenen)   


## In ... op ... met ...
begraven op (.*?) \[†\]\(#notitie\) --> begraven tussen [†](#notitie)
begraven op(.*?)\[†\]
begraven 26-06/03-07-1773[†](#notitie)

in ... op ... met ...
tr. (\w+){1,4} (\d\d-\d\d-\d\d\d\d) (\w+){1,4}
tr. op $1 met $2

tr\. (?!(op|in)\b)((\w+\s?){1,4}) \d{2}-\d{2}-\d{4} (\w+){1,4}

tr\. (?!(op|in)\b)
tr\. (?!(op|in|met)\b)

tr\. .*? \(?\)

overleden.*?(?!(op|in)\b) (\d\d-\d\d-\d\d\d\d)

geboren (\d\d-\d\d-\d\d\d\d) (405 matches)
geboren op $1

geboren (?!(op|in|en|ca)\b) (bij regel 933) vervangen met geboren in 


ondertrouw ((\w+\s?){1,4}) (\d\d-\d\d-\d\d\d\d) (\w+){1,4}
ondertrouw in $1 op $2 met $3

ondertrouw (\d\d-\d\d-\d\d\d\d) (\w+){1,4}
ondertrouw op $1 met $2

ondertrouw (?!(op|in)\b)((\w+\s?){1,4}) (\d\d-\d\d-\d\d\d\d)
ondertrouw op $1 met $2


ondertrouw (\d\d-\d\d-\d\d\d\d)
ondertrouw op $1

ondertrouw (?!(op|in)\b)((\w+\s?){1,4}) (\d\d-\d\d-\d\d\d\d)

ondertrouw (\d\d-\d\d-\d\d\d\d) (\(.*?\)) 
ondertrouw op $1 $2 met 

otr./tr. in ... op ... (getuige ...) met ...


ondertrouw op 09-10-1682 met Marritje Floris van Leeuwen (getuige zijn stiefmoeder Maria Belterman),
ondertrouw (op)? (\d\d-\d\d-\d\d\d\d) met ((\w+\s?){1,4}) \(

ondertrouw (?!(op|in|met)\b)
ondertrouw (?!(op)\b)

volgt (\[.*\))  $
(\[†.*\))  $

^\d\d?\. .*\.  $
