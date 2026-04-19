# AddressArray.sol
AddressArray.sol
pragma solidity ^0.8.20;
contract AddressArray {
    address[] public users;

    function add() public {
        users.push(msg.sender);
    }
}
