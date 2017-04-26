# EMVSourceVerification
Trying To Verify The Source Code For The EMV Token

The EMV "Ethereum Movie Venture" token was deployed to [0xb802b24e0637c2b87d2e8b7784c055bbe921011a](https://etherscan.io/address/0xb802b24e0637c2b87d2e8b7784c055bbe921011a) but the source code was not uploaded to EtherScan.io for source verification at that time.

The transaction that deployed the contract 161 days 6 hrs ago (Nov-15-2016 06:37:55 PM +UTC) is [0xc322dbdd...](https://etherscan.io/tx/0xc322dbdd99d95efb10b51e647f15e6540b7533e10eb88be8eda5f3c7d027bf48) and has the following data (in [bytecode/DeployedBytecode.txt](bytecode/DeployedBytecode.txt)):

> 0x60a060405260096060527f546f6b656e20302e310000000000000000000000000000000000000000000000608052600080548180527f546f6b656e20302e31000000000000000000000000000000000000000000001282556100b3907f290decd9548b62a8d60345a988386fc84ba6bc95484008f6362f93160ef3e563602060026001841615610100026000190190931692909204601f01919091048101905b80821115610181576000815560010161009f565b50506040516108be3803806108be83398101604052808051906020019091908051820191906020018051906020019091908051820191906020015050600160a060020a0333166000908152600560209081526040822086905560048690558451600180549381905292600281851615610100026000190190911604601f9081018390047fb10e2d527612073b26eecdfd717e6a320cf44b4afac2b0732d9fcbe2b7fa0cf69081019390919088019083901061018557805160ff19168380011785555b506101b592915061009f565b5090565b82800160010185558215610175579182015b82811115610175578251826000505591602001919060010190610197565b50508060026000509080519060200190828054600181600116156101000203166002900490600052602060002090601f016020900481019282601f1061020e57805160ff19168380011785555b5061023e92915061009f565b82800160010185558215610202579182015b82811115610202578251826000505591602001919060010190610220565b50506003805460ff191683179055505050506106608061025e6000396000f36060604052361561008d5760e060020a600035046306fdde03811461009a578063095ea7b3146100fc57806318160ddd1461010f57806323b872dd1461011d578063313ce567146101545780635a3b7e421461016557806370a08231146101c857806395d89b41146101e5578063a9059cbb14610245578063cae9ca5114610279578063dd62ed3e14610303575b346100025761032d610002565b346100025760408051600180546020600282841615610100026000190190921691909104601f810182900482028401820190945283835261032f93908301828280156104045780601f106103d957610100808354040283529160200191610404565b346100025761039d6004356024356102d3565b34610002576103b160045481565b346100025761039d600435602435604435600160a060020a0383166000908152600560205260408120548290101561040c57610002565b34610002576103c360035460ff1681565b34610002576040805160008054602060026001831615610100026000190190921691909104601f810182900482028401820190945283835261032f93908301828280156104045780601f106103d957610100808354040283529160200191610404565b34610002576103b160043560056020526000908152604090205481565b346100025761032f6002805460408051602060018416156101000260001901909316849004601f810184900484028201840190925281815292918301828280156104045780601f106103d957610100808354040283529160200191610404565b346100025761032d600435602435600160a060020a033316600090815260056020526040902054819010156104f157610002565b3461000257604080516020604435600481810135601f810184900484028501840190955284845261039d94813594602480359593946064949293910191819084018382808284375094965050505050505060008361058381855b600160a060020a033381166000908152600660209081526040808320938616835292905220819055600192915050565b34610002576006602090815260043560009081526040808220909252602435815220546103b19081565b005b60405180806020018281038252838181518152602001915080519060200190808383829060006004602084601f0104600302600f01f150905090810190601f16801561038f5780820380516001836020036101000a031916815260200191505b509250505060405180910390f35b604080519115158252519081900360200190f35b60408051918252519081900360200190f35b6040805160ff9092168252519081900360200190f35b820191906000526020600020905b8154815290600101906020018083116103e757829003601f168201915b505050505081565b600160a060020a038316600090815260056020526040902054808301101561043357610002565b600160a060020a038481166000908152600660209081526040808320339094168352929052205482111561046657610002565b600160a060020a03848116600081815260056020908152604080832080548890039055878516808452818420805489019055848452600683528184203390961684529482529182902080548790039055815186815291517fddf252ad1be2c89b69c2b068fc378daa952ba7f163c4a11628f55a4df523b3ef9281900390910190a35060019392505050565b600160a060020a038216600090815260056020526040902054808201101561051857610002565b600160a060020a03338116600081815260056020908152604080832080548790039055938616808352918490208054860190558351858152935191937fddf252ad1be2c89b69c2b068fc378daa952ba7f163c4a11628f55a4df523b3ef929081900390910190a35050565b156106585780600160a060020a0316638f4ffcb1338630876040518560e060020a0281526004018085600160a060020a0316815260200184815260200183600160a060020a03168152602001806020018281038252838181518152602001915080519060200190808383829060006004602084601f0104600302600f01f150905090810190601f16801561062b5780820380516001836020036101000a031916815260200191505b5095505050505050600060405180830381600087803b156100025760325a03f11561000257505050600191505b509392505050560000000000000000000000000000000000000000000000000000000027bc86680000000000000000000000000000000000000000000000000000000000000080000000000000000000000000000000000000000000000000000000000000000200000000000000000000000000000000000000000000000000000000000000c00000000000000000000000000000000000000000000000000000000000000014457468657265756d4d6f76696556656e747572650000000000000000000000000000000000000000000000000000000000000000000000000000000000000003454d560000000000000000000000000000000000000000000000000000000000

The deployment constructor data follows:

    0000000000000000000000000000000000000000000000000000000027bc8668 // new BigNumber("27bc8668",16) => 666666600
    0000000000000000000000000000000000000000000000000000000000000080
    0000000000000000000000000000000000000000000000000000000000000002 // decimal units
    00000000000000000000000000000000000000000000000000000000000000c0
    0000000000000000000000000000000000000000000000000000000000000014
    457468657265756d4d6f76696556656e74757265000000000000000000000000 // web3.toUtf8("457468657265756d4d6f76696556656e74757265") => "EthereumMovieVenture"
    0000000000000000000000000000000000000000000000000000000000000003 // 3
    454d560000000000000000000000000000000000000000000000000000000000 // web3.toUtf8("454d56") => "EMV"
    

From https://github.com/ethereum/solidity/releases?after=v0.4.5, Solidity v0.4.4 was released Nov 01 2016, v0.4.3 was released Oct 26 2016, v0.4.2 was released Sep 17 2016.