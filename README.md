# VirtualDQC

Limitations in single Quantum Proccessing Units (QPU's), namely, their low qubit counts, have generated plenty of interest in modular architectures, which aim to string together many chips in a bid to reach utility scale qubit counts. For example, quantum algorithms with a theoretically proven advantage over classical ones such as Shor's and Grovers require currently intractable single-chip qubit counts to truly reach their potential. 

However, contemporary methods of connecting QPU's are still in their infancy. One technique, using photons and beamsplitter operations suffer terribly from noise and can be 300x more costly than intra-chip operations. For this reason, a versatile simulation method must be developed.

This repo walks through a basic VDQC experiment including; generating a virtual backend, developing a logical-to-backend qubit map, transpiling a partitioned circuit given by DisQCO and implemeneting communication qubit specific noise models.
