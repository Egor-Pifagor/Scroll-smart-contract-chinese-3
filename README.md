# Scroll-smart-contract-chinese-3
 // 合约内的函数可以调用内部函数     function minusCall() external {         minus();     }      // payable: 递钱，能给合约支付eth的函数     function minusPayable() external payable returns(uint256 balance) {         minus();             balance = address(this).balance;     } }
