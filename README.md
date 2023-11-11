# Check-if-a-String-Is-an-Acronym-of-words-using-Java-Leetcode

    class Solution {
        public boolean isAcronym(List<String> words, String s) {
            if(words.size() != s.length()){
                return false;
            }
            for(int i =0; i< words.size();i++){
                if(words.get(i).charAt(0)== s.charAt(i)){
                    continue;
                }else{
                    return false;
                }
            }
            return true;
        }
    }
