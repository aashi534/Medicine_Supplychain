const HDWalletProvider = require('truffle-hdwallet-provider');
const infuraKey = "https://ropsten.infura.io/v3/3a8022cbb64b4013aebd3abe1b0414cb";

module.exports = {

  networks: {
    development: {
      host: "127.0.0.1",
      port: 7545,
      network_id: "*" // Match any network id
    },
    ropsten:{
      provider: function(){return new HDWalletProvider("reform merry pudding tiny sign list awful approve cross genre initial nurse",infuraKey) ;},
      network_id:'*',
      gas:4500000,
      gasPrice:1000000000,
    }
  },
  compilers: {
    solc: {
      version: "0.4.24" // ex:  "0.4.20". (Default: Truffle's installed solc)
    }
  }
};
