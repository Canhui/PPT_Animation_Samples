## 1. PPT_Animation_Samples
Please find the Hands-on Tutorial in [[MS Doc](https://github.com/Canhui/Hyperledger_Fabric_Phase_Bench/blob/main/Hands-on-tutorial/Hands-on-Tutorial.docx), 4.18 MB, 109 Pages] or in [[PDF](https://github.com/Canhui/Hyperledger_Fabric_Phase_Bench/blob/main/Hands-on-tutorial/Hands-on-Tutorial.pdf), 3.60 MB, 109 Pages].



## 2. Preparation

#### 2.1. Cluster Environment

Please see [section A](https://github.com/Canhui/Hyperledger_Fabric_Phase_Bench/blob/main/Hands-on-tutorial/Hands-on-Tutorial.pdf) of the tutorial for preparation of multiple computing nodes on the cloud.


#### 2.2. Si

#### 2.3. Workload Generator

<ul>
  <li> Q1: How to generate a transaction via Node.js SDK?
    <ul>
      <li>For invoke a transaction, please see <a href="https://github.com/Canhui/Hyperledger_Fabric_Phase_Bench/blob/main/Exp03-fabric-samples/demo-first/workload/sdk-peer0-org1/invoke.js">invoke.js</a> under the workload folder.</li>
      <li>For query a transaction, please see <a href="https://github.com/Canhui/Hyperledger_Fabric_Phase_Bench/blob/main/Exp03-fabric-samples/demo-first/workload/sdk-peer0-org1/query.js">query.js</a> under the worklaod folder.</li>
    </ul>
  </li>

  <li> Q2: How to generate some transactions using a client?
    <ul>
      <li>For invoke some transactions, please see <a href="https://github.com/Canhui/Hyperledger_Fabric_Phase_Bench/blob/main/Exp03-fabric-samples/demo-first/workload/ssh.sh">ssh.sh</a> under the workload folder.</li>
      <li>For query some transactions, please see <a href="https://github.com/Canhui/Hyperledger_Fabric_Phase_Bench/blob/main/Exp03-fabric-samples/demo-first/workload/ssh.sh">ssh.sh</a> under the worklaod folder.</li>
    </ul>
  </li>

  <li> Q3: How to stably generate many transactions using many clients?
    <ul>
      <li>For stably invoke many transactions, please see <a href="https://github.com/Canhui/Hyperledger_Fabric_Phase_Bench/blob/main/Exp03-fabric-samples/demo-first/workload/ssh.sh">ssh.sh</a> under the workload folder.</li>
      <li>For stably query many transactions, please see <a href="https://github.com/Canhui/Hyperledger_Fabric_Phase_Bench/blob/main/Exp03-fabric-samples/demo-first/workload/ssh.sh">ssh.sh</a> under the worklaod folder.</li>
    </ul>
  </li>
</ul>





## License

Samples is available under the MIT License (Year 2026).


## Reference
[1. PPT Animation Videos] https://www.bilibili.com/video/BV1ax411Z7RU/?vd_source=e422e2614baa36cb808376bf194b6359&spm_id_from=333.788.videopod.episodes <br>
[2. Hyperledger Fabric Dynamic Channel Update] https://hyperledger-fabric.readthedocs.io/en/release-2.2/config_update.html <br>
[3. Hyperledger Fabric SDK for node.js] https://hyperledger.github.io/fabric-sdk-node/release-1.4/module-fabric-network.html
