# mood.sol
// SPDX-License-Identifier: GPL-3.0
pragma solidity ^0.8.4;

contract MoodDiary {
     
    string mood;

    //This will set Mood
    function setMood(string memory _mood) public{
     mood = _mood;
    }

    //This will get Mood
    function getMood() public view returns(string memory){
     return mood;
    }
}
