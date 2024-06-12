// SPDX-License-Identifier: MIT
pragma solidity 0.8.18;

contract newMyToken {
    string public nwTokenName = "AMISHA";
    string public nwTokenAbbrv = "SID";
    uint public nwTotalValue = 0;

    mapping(address => uint) public nwbalances;
    
    function nwmint (address _address, uint_value) public{ 

       nwTotalValue += _value;

       nwbalances[_address] += _value;

}

   function nwburn (address _address, uint_value) public {

   if (nwbalances [_address] >= _value){

      nwTotalValue -= _value;

      nwbalances[_address] -= _value;}
    }
   

  
 }
