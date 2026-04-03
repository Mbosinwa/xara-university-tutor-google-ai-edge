---
courseName: Data Communication and Networks
courseCode: CMS703
subjectDomain: Computer Science
materialsCount: 6
status: Active
created: 2026-03-09
lastUpdated: 2026-03-30
---

# Course Structure: Data Communication and Networks

## Materials Index

| # | Material | Type | Status |
|---|----------|------|--------|
| 1 | cms703-course-outline.md | Direct Text | ✓ Processed |
| 2 | introduction-to-fourier-series-transcript.md | YouTube Transcript | ✓ Processed |
| 3 | data-communications-lecture-1-section-1-introduction-transcript.md | YouTube Transcript | ✓ Processed |
| 4 | introduction-to-data-communication-networks-lecture-1-transcript.md | YouTube Transcript | ✓ Processed |
| 5 | what-is-networking-osi-model-transcript.md | YouTube Transcript | ✓ Processed |
| 6 | cms703-lecture-notes-dr-saturday.md | Lecture Notes (File) | ✓ Processed |

---

## Topics

### Primary Topics

1. **Introduction to Data Communication**
   - Definition of Data Communication
   - Components of a Data Communication System
     - Message
     - Sender
     - Receiver
     - Transmission Medium
     - Protocol
   - Data Representation Forms (Text/Numbers, Images, Audio, Video)
   - Fundamental Principles: Delivery, Accuracy, Timeliness

2. **Fourier Analysis**
   - Fourier Series Expansion
     - Continuous Time Fourier Series
     - Discrete Time Fourier Series
   - Fourier Transform
     - Continuous Time Fourier Transform
     - Discrete Time Fourier Transform
   - Types of Fourier Series: Trigonometric, Complex Exponential, Polar/Harmonic
   - Dirichlet Conditions (existence of Fourier Series)
   - Harmonics (odd and even)
   - Periodic vs Non-periodic Signals

3. **Data Transmission Modes**
   - Simplex Mode
   - Half-Duplex Mode
   - Full-Duplex Mode

4. **Data Transmission Forms**
   - Analog Transmission
   - Digital Transmission

5. **Data Transmission Speed**
   - Bandwidth
   - Bits per Second (BPS)

6. **Transmission Media**
   - Guided Media
     - Twisted Pair Wire (STP, UTP)
     - Coaxial Cable
     - Optical Fiber
   - Unguided Media
     - Microwave Systems (Terrestrial, Satellite)
     - Communication Satellites

7. **Computer Networks**
   - Types of Networks
     - LAN (Local Area Network)
     - MAN (Metropolitan Area Network)
     - WAN (Wide Area Network)
   - Network Topologies
     - Star Topology
     - Ring Topology
     - Bus Topology
     - Mesh Topology

8. **Switching Techniques**
   - Circuit Switching
   - Packet Switching

9. **Routing Techniques**
   - Source Routing
   - Hop-by-Hop Routing
   - Difference between Switching and Routing

10. **Communication Protocols**
    - Definition and Purpose
    - Protocol Functions (packet size, numbering, error control, security, routing)
    - Standards and Standards Organisations

11. **OSI Model**
    - Layer 1: Physical Layer
    - Layer 2: Data Link Layer
    - Layer 3: Network Layer
    - Layer 4: Transport Layer
    - Layer 5: Session Layer
    - Layer 6: Presentation Layer
    - Layer 7: Application Layer
    - Network Interface Card (NIC)

12. **Measures of Communication**
13. **Channel Characteristics**
14. **Noise and Distortion**
15. **Modulation and Demodulation**
16. **Multiplexing**
    - TDM (Time Division Multiplexing)
    - FDM (Frequency Division Multiplexing)
    - FCM (Frequency Code Multiplexing)
17. **Parallel and Serial Transmission**
18. **Bus Structure and Loop System**
19. **Broadcast Techniques**
20. **Network Structure for Packet Switching**
21. **Serial vs Parallel Data Transmission**
    - Serial Transmission (bit-by-bit, single channel)
    - Parallel Transmission (multiple bits simultaneously, multiple channels)
    - Advantages and Disadvantages of each
    - Long-distance communication examples (telephony, fibre, satellite, WiFi)
    - Embedded systems serial applications (RS-232, RS-485, SPI, DNP3)
22. **Asynchronous and Synchronous Transmission**
    - Asynchronous: character-by-character framing, Start/Stop bits
    - Synchronous: block/frame transmission, clock-based synchronization
    - Frame structures for both modes
    - Error detection: Parity bit (async), CRC/checksum (sync)
23. **Data Representation (Detailed)**
    - Text: Unicode (32-bit), ASCII (127 chars / Basic Latin)
    - Images: Pixel matrix, RGB and YCM colour models
    - Audio: Continuous signal, sampling and quantization
    - Video: Analog or digital, encoding process
24. **Bandwidth Allocation in Communication (Real-World OFDM/5G)**
    - Modeling signals as square pulses
    - Applying Fourier Transform → Sinc spectrum
    - OFDM (Orthogonal Frequency Division Multiplexing) in 5G and LTE

---

## Key Concepts

| Concept | Brief Description | Source Material |
|---------|-------------------|-----------------|
| Data Communication | Process of transferring electronic/digital data between two or more nodes | lecture transcripts |
| Message | The information to be communicated (text, numbers, images, audio, video) | lecture transcripts |
| Sender | Device that sends the data message | lecture transcripts |
| Receiver | Device that receives the message | lecture transcripts |
| Transmission Medium | Physical path by which a message travels from sender to receiver | lecture transcripts |
| Protocol | Set of rules governing data communication between devices | lecture transcripts |
| Simplex | Data flows in one direction only | lecture transcripts |
| Half-Duplex | Data flows in both directions but not simultaneously | lecture transcripts |
| Full-Duplex | Data flows in both directions simultaneously | lecture transcripts |
| Analog Transmission | Transmission of data in a continuous waveform | what-is-networking-osi-model-transcript.md |
| Digital Transmission | Transmission using distinct on/off electrical states (0 or 1) | what-is-networking-osi-model-transcript.md |
| LAN | Local Area Network — connects devices within a limited geographical area | what-is-networking-osi-model-transcript.md |
| MAN | Metropolitan Area Network — covers a large city or area | what-is-networking-osi-model-transcript.md |
| WAN | Wide Area Network — interconnects LANs and MANs over unrestricted geography | what-is-networking-osi-model-transcript.md |
| Star Topology | All computers connected to a central hub/switch | what-is-networking-osi-model-transcript.md |
| Ring Topology | Computers connected in a closed cable loop | what-is-networking-osi-model-transcript.md |
| Bus Topology | All nodes connected to a single backbone cable | what-is-networking-osi-model-transcript.md |
| Mesh Topology | Every node interconnected with every other node | what-is-networking-osi-model-transcript.md |
| Twisted Pair Wire | Copper wires twisted together; two types: STP and UTP | what-is-networking-osi-model-transcript.md |
| Coaxial Cable | Single copper conductor with shield; used for longer distances | what-is-networking-osi-model-transcript.md |
| Optical Fiber | Glass fiber transmitting data as light signals | what-is-networking-osi-model-transcript.md |
| Circuit Switching | Dedicated physical path established for duration of connection | what-is-networking-osi-model-transcript.md |
| Packet Switching | Data divided into packets; each routed independently | what-is-networking-osi-model-transcript.md |
| OSI Model | 7-layer reference model for network communication (ISO, 1984) | what-is-networking-osi-model-transcript.md |
| Physical Layer | Layer 1 — deals with bit stream over physical medium | what-is-networking-osi-model-transcript.md |
| Data Link Layer | Layer 2 — responsible for frame transmission over network | what-is-networking-osi-model-transcript.md |
| Network Layer | Layer 3 — routing from source to destination | what-is-networking-osi-model-transcript.md |
| Transport Layer | Layer 4 — end-to-end delivery, error control, flow control | what-is-networking-osi-model-transcript.md |
| Session Layer | Layer 5 — manages sessions/dialogues between computers | what-is-networking-osi-model-transcript.md |
| Presentation Layer | Layer 6 — syntax, encryption, compression | what-is-networking-osi-model-transcript.md |
| Application Layer | Layer 7 — user interface and network services | what-is-networking-osi-model-transcript.md |
| NIC | Network Interface Card — hardware connecting computer to network | what-is-networking-osi-model-transcript.md |
| Fourier Series | Expands periodic signals into sinusoidal harmonics | introduction-to-fourier-series-transcript.md |
| Fourier Transform | Analysis tool for non-periodic signals | introduction-to-fourier-series-transcript.md |
| Laplace Transform | Design tool for continuous-time systems (transfer functions) | introduction-to-fourier-series-transcript.md |
| Z Transform | Discrete-time equivalent of Laplace transform | introduction-to-fourier-series-transcript.md |
| Periodic Signal | Signal that repeats itself at regular time intervals | introduction-to-fourier-series-transcript.md |
| Fundamental Frequency | The base frequency (Ω) from which harmonics are derived | introduction-to-fourier-series-transcript.md |
| Harmonic | Frequency component at an integral multiple of the fundamental frequency | introduction-to-fourier-series-transcript.md |
| Dirichlet Conditions | Three conditions required for Fourier Series to exist | introduction-to-fourier-series-transcript.md |
| Orthogonality | Property of harmonics — independent of one another | introduction-to-fourier-series-transcript.md |
| Modulation | Encoding information onto a carrier signal | cms703-course-outline.md |
| Serial Transmission | Bits sent one-at-a-time over a single channel; reliable over long distances | cms703-lecture-notes-dr-saturday.md |
| Parallel Transmission | Multiple bits sent simultaneously over multiple channels; fast but short-distance only | cms703-lecture-notes-dr-saturday.md |
| Asynchronous Transmission | Character-framed with Start/Stop bits; no shared clock; simple but overhead-heavy | cms703-lecture-notes-dr-saturday.md |
| Synchronous Transmission | Block/frame-based; clock-synchronized; efficient for bulk data | cms703-lecture-notes-dr-saturday.md |
| Unicode | 32-bit character encoding system used globally; ASCII (127 chars) is a subset (Basic Latin) | cms703-lecture-notes-dr-saturday.md |
| Pixel | Smallest unit in a digital image; assigned a bit pattern based on colour/intensity | cms703-lecture-notes-dr-saturday.md |
| Quantization | Approximating a sampled analog signal with a finite set of values then encoding as bit patterns | cms703-lecture-notes-dr-saturday.md |
| OFDM | Orthogonal Frequency Division Multiplexing — core 5G/LTE technology based on Fourier Transform principles | cms703-lecture-notes-dr-saturday.md |
| Fourier Transform of Square Pulse | F(ω) = T·sinc(ωT/2) — shows signal contains many frequencies; wider pulse = narrower frequency spread | cms703-lecture-notes-dr-saturday.md |
| Multiplexing | Combining multiple signals over a shared medium | cms703-course-outline.md |
| Bandwidth | Measure of data transfer capacity over a network per unit time | what-is-networking-osi-model-transcript.md |

---

## Definitions

### Data Communication
The process of using computing and communication technologies to transfer data from one place to another; enables the movement of electronic or digital data between two or more network nodes regardless of geographical location, transmission medium, or data content.
*Source: data-communications-lecture-1-section-1-introduction-transcript.md*

### Protocol
A set of rules that governs data communication. It represents the agreement between communication devices; without a protocol, two devices may be connected but not communicating.
*Source: lecture transcripts*

### Simplex Mode
Data communication is unidirectional — the sender can only send, the receiver can only receive. Examples: keyboard → computer, computer → monitor, radio/TV broadcast.
*Source: data-communications-lecture-1-section-1-introduction-transcript.md*

### Half-Duplex Mode
Data can flow in both directions but only one direction at a time. Examples: walkie-talkies, citizens band radios, Ethernet hubs, USB 2.0.
*Source: data-communications-lecture-1-section-1-introduction-transcript.md*

### Full-Duplex Mode
Data flows in both directions simultaneously. Examples: telephone, router with switches, duplex fiber optic cable, USB 3.0.
*Source: data-communications-lecture-1-section-1-introduction-transcript.md*

### OSI Model
The Open System Interconnection model — released 1984 by ISO. Describes data transmission in 7 layers from Physical (hardware) to Application (user interface).
*Source: what-is-networking-osi-model-transcript.md*

### Circuit Switching
A dedicated circuit is built during transmission. A physical path is created for a single connection for the entire duration. Example: PTCL public telephone network.
*Source: what-is-networking-osi-model-transcript.md*

### Packet Switching
Data converted into small packets each containing routing header information; packets are independent and routed separately. Example: the Internet.
*Source: what-is-networking-osi-model-transcript.md*

### Optical Fiber
A slim, flexible glass fiber medium transmitting data as light signals. Features: low attenuation, immune to electromagnetic interference, small size, high capacity.
*Source: what-is-networking-osi-model-transcript.md*

### Fourier Series
Expansion used for periodic signals to represent them as a sum of sinusoidal harmonics that are orthogonal to one another.
*Source: introduction-to-fourier-series-transcript.md*

### Periodic Signal
A signal in which a particular structure repeats itself from minus infinity to infinity; formally: X(T ± T₀) = X(T), where T₀ is the time period.
*Source: introduction-to-fourier-series-transcript.md*

### Fundamental Time Period (T₀)
The smallest time interval for which a given signal is periodic.
*Source: introduction-to-fourier-series-transcript.md*

### Harmonic
A frequency component whose frequency is an integral multiple of the fundamental frequency Ω. Odd harmonics have odd integer multipliers; even harmonics have even integer multipliers.
*Source: introduction-to-fourier-series-transcript.md*

### Serial Data Transmission
Data transmitted one bit after another over a single communication channel. Sequential travel of bits. Reliable over long distances (less signal distortion). Used in USB, Ethernet, RS-232, fibre optic backbones.
*Source: cms703-lecture-notes-dr-saturday.md*

### Parallel Data Transmission
Multiple bits transmitted simultaneously across multiple channels/wires. Transfers an entire word (byte) at once. Fast but only suitable for short distances due to interference and skew.
*Source: cms703-lecture-notes-dr-saturday.md*

### Asynchronous Transmission
Character-by-character framing using Start and Stop bits. No shared clock — synchronization happens at the character level. Frame: [Start bit | D0–D7 | Parity | Stop bit].
*Source: cms703-lecture-notes-dr-saturday.md*

### Synchronous Transmission
Data transferred in blocks/frames without Start/Stop bits. Sender and receiver synchronized by a shared clock or special signals. Error detection via CRC or checksum.
*Source: cms703-lecture-notes-dr-saturday.md*

### OFDM (Orthogonal Frequency Division Multiplexing)
A core technology in 5G and LTE (Long Term Evolution) that allocates frequency bands based on the Fourier Transform of digital signals — enables efficient use of spectrum by distributing data across many subcarriers.
*Source: cms703-lecture-notes-dr-saturday.md*

### Dirichlet Conditions
Three necessary conditions that a periodic signal must satisfy for its Fourier Series expansion to exist.
*Source: introduction-to-fourier-series-transcript.md*

---

## Examples

### Simplex Examples
Keyboard/mouse → computer (input only); computer → monitor (output only); computer → printer; radio/TV broadcast.
*Source: data-communications-lecture-1-section-1-introduction-transcript.md*

### Half-Duplex Examples
Walkie-talkies (say "over" to hand over); Ethernet hubs (shared medium, one device transmits at a time); USB 2.0.
*Source: data-communications-lecture-1-section-1-introduction-transcript.md*

### Full-Duplex Examples
Telephone (both parties speak/listen simultaneously); router + switches with duplex fiber; USB 3.0.
*Source: data-communications-lecture-1-section-1-introduction-transcript.md*

### Circuit Switching Example
PTCL public telephone network — a physical path is reserved for the call duration.
*Source: what-is-networking-osi-model-transcript.md*

### Packet Switching Example
The Internet — data split into packets each routed independently to the destination.
*Source: what-is-networking-osi-model-transcript.md*

### Harmonic Decomposition Example
Signal X(T) = 2sin(ΩT) + sin(2ΩT) + 7sin(3ΩT). 2sin(ΩT) is the fundamental; sin(2ΩT) is 2nd (even) harmonic; 7sin(3ΩT) is 3rd (odd) harmonic — dominant due to coefficient 7.
*Source: introduction-to-fourier-series-transcript.md*

### Serial Transmission Examples
Telephone Network (T1/E1 lines), Fibre Optic backbone, Satellite communication, WiFi/4G/5G.
*Source: cms703-lecture-notes-dr-saturday.md*

### Parallel Transmission Examples
Computer buses, CPU data bus, internal memory transfer, printer connections.
*Source: cms703-lecture-notes-dr-saturday.md*

### Asynchronous Transmission Applications
RS-232 serial ports, keyboard/mouse communication, early dial-up modems.
*Source: cms703-lecture-notes-dr-saturday.md*

### Synchronous Transmission Applications
Ethernet networks, broadband communication, digital telephony, satellite/wireless systems.
*Source: cms703-lecture-notes-dr-saturday.md*

### Non-periodic Signal Example
Human voice captured by microphone — non-periodic, requires Fourier Transform not Fourier Series.
*Source: introduction-to-fourier-series-transcript.md*

---

## Relationships

| From | Relationship | To |
|------|-------------|----|
| Protocol | governs communication in | Computer Networks |
| Protocol | is required for | Data Communication between devices |
| Simplex | contrasts-with | Half-Duplex and Full-Duplex |
| Half-Duplex | contrasts-with | Full-Duplex |
| Full-Duplex | enables | Simultaneous Bidirectional Communication |
| Transmission Medium | is-a part-of | Data Communication System |
| Guided Media | is-a type-of | Transmission Media |
| Unguided Media | is-a type-of | Transmission Media |
| Twisted Pair | is-a type-of | Guided Media |
| Coaxial Cable | is-a type-of | Guided Media |
| Optical Fiber | is-a type-of | Guided Media |
| Microwave | is-a type-of | Unguided Media |
| Satellite | is-a type-of | Unguided Media |
| LAN | is-a type-of | Computer Network |
| MAN | is-a type-of | Computer Network |
| WAN | is-a type-of | Computer Network |
| Star Topology | is-a type-of | Network Topology |
| Ring Topology | is-a type-of | Network Topology |
| Bus Topology | is-a type-of | Network Topology |
| Mesh Topology | is-a type-of | Network Topology |
| Circuit Switching | contrasts-with | Packet Switching |
| Circuit Switching | requires | Dedicated path for connection |
| Packet Switching | enables | Internet communication |
| OSI Model | consists-of | 7 Layers (Physical to Application) |
| Physical Layer | is Layer 1 of | OSI Model |
| Data Link Layer | is Layer 2 of | OSI Model |
| Network Layer | is Layer 3 of | OSI Model |
| Transport Layer | is Layer 4 of | OSI Model |
| Session Layer | is Layer 5 of | OSI Model |
| Presentation Layer | is Layer 6 of | OSI Model |
| Application Layer | is Layer 7 of | OSI Model |
| Network Layer | handles | Routing |
| Transport Layer | handles | End-to-end delivery and flow control |
| Presentation Layer | handles | Encryption and data compression |
| Routing | is-a type-of | Switching Technique |
| Fourier Series | is used for analysis of | Periodic Signals |
| Fourier Transform | is used for analysis of | Non-periodic Signals |
| Laplace Transform | is used for design of | Continuous-time Systems |
| Z Transform | is the discrete-time equivalent of | Laplace Transform |
| Harmonic | is an integral multiple of | Fundamental Frequency |
| Periodic Signal | must satisfy | Dirichlet Conditions |
| Modulation | is the encoding mechanism for | Transmission Media |
| Multiplexing | combines signals for | Shared Channel Transmission |
| Packet Switching | is the basis of | Network Structure |
| Analog Transmission | contrasts-with | Digital Transmission |
| Bandwidth | measures | Data Transmission Speed |
| Serial Transmission | transmits data | one bit at a time over a single channel |
| Parallel Transmission | transmits data | multiple bits simultaneously over multiple channels |
| Asynchronous Transmission | uses | Start/Stop bits per character frame |
| Synchronous Transmission | uses | block/frame structure with clock synchronization |
| Unicode | encodes | text using 32-bit patterns (includes ASCII as Basic Latin) |
| RGB | is a method for | representing colour images using bit patterns |
| YCM | is a method for | representing colour images using bit patterns |
| Pixel | is the unit of | image representation in digital images |
| Sampling/Quantization | converts | continuous audio/video signals to digital |
| OFDM | is-a application-of | Fourier Transform in 5G and LTE networks |
| RS-232 / RS-485 | are types-of | serial communication protocols used in embedded/SCADA systems |
