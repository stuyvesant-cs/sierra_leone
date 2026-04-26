## Digital Data

Computers use number to represent all the information that they work with. This kind of information is referred to as _digital data_. All digital data is (eventually) stored and transmitted as binary numbers, which means the numbers are only made up of 0s and 1s. When we talk about the size of a computer file, or the speed of a network connection, we are talking about how many 0s and 1s are being used.
- A __bit__ is a unit of measurement that equals a single BInary digiT (a 0 or 1). A bit is the smallest amount of information possible in computing.
- A __byte__ is a unit of measurement equal to 8 bits.
We use __b__ to signify bits and __B__ is for bytes

When we measure how long something is, we use meters, and when we measure things that are really long, we use _kilo_meters, or 1000 meters. We do a similar thing with digital data with the following prefixes:
- Kilo (K): 1,000 (one thousand)
- Mega (M): 1,000,000 (one million)
- Giga (G): 1,000,000,000 (one billion)
- Tera (T): 1,000,000,000,000 (one trillion)

If you have a picture on a computer, and it is 3MB (megabytes) large, that picture is represented as 24 _million_ bits:
- 3 Megabytes = 3,000,000 bytes.
- 3,000,000 bytes * 8 bits per byte = 24,000,000 bits.
You don't need to do this conversion all the time, but it is helpful to understand that bits and bytes are real measurements of the amount of 0s and 1s needed to represent the data you are working with.

When we talk about internet connection speeds, we measure in how many bits can be transferred in a single second. If your internet download speed is 12 Mb/s (megabits per second), then if you take 2 seconds to download the 24 million bits needed for a 3MB picture file.



## Computer Hardware

_Hardware_ are the physical parts that make up computers. Normally, we don't interact with the actual bits of computer information, instead, we interact with hardware like keyboards, monitors, touch screens and so on. In general, there are two different categories of hardware, the digital components that work with bits to save and manipulate data, and the support structures that help the digital components do their jobs.


### Digital Hardware Components
Theses are the devices that help store and manipulate digital data. While the are many variations of theses components, generally speaking they fall into these categories:
- Processor
- Short term data retention (memory)
- Long term data storage
- Input and Output

#### Processor (CPU)
The main processor of a computer is usually called the Central Processing Unit, or CPU. It is a "computer chip", made up of billions of tiny components called _transistors_. The CPU is the "brain" of the computer, performing the basic instructions that computer programs are broken up into. Sometimes those instructions involve doing math with bits, other times they involve moving bits from one component to another. If your computer is "working" on something, that work is being done by the CPU.

A CPU works in _cycles_
- First, the CPU reads in values or instructions as a set of bits.
- The CPU then works on those bits, often performing calculations, and creates a result.
- The CPU sends that result out as a new set of bits.
- These three steps are a single _cycle_.

When we talk about the speed of a processor, we refer to the number of cycles it can run in a second, and the units we use are called _Hertz_. So a 2 _GHz_ (gigahertz) processor can perform two billion cycles in a single second. Even though processors can perform billions of operations every second, they can only do one operation each cycle. Sometimes, a processor can have more than one _core_, each core is actually a separate processor that the put on the same computer chip. Each core has its own set of input bits and output bits, so if a computer has 4 cores, it can actually perform 4 operations each cycle, increasing the amount of work it can do.


#### Storage
- Long term data retention.
- Non-volatile: Retains data without needing a power supply.
- Binary data can be represented in many different ways on storage devices, the most common being:
  - Magnetic charges (+/-)
  - Electricity (low/high voltage)
  - Optical (changes in reflective coating)
- Example devices:
  - SSDs, Flash Drives (Electricity)
  - Hard Disk Drives (Magnetic charges)
  - DVDs, CDs (Optical)

#### Memory
- Short term, fast data access.
- Only used by what the computer is actively running.
- Volatile: Needs electricity to store the data.
- Examples: RAM (Random Access Memory), Swap


#### Storage & Memory
- All saved data exists in storage.
- Anything that a computer is actively using is in memory.
- In order for a computer to use a stored file of any type, the file must be copied from storage into memory (loading).
- Saving a file means taking the version currently in memory and writing it back to storage.

### Support Hardware
- Motherboard
- Power supply
- Cooling
- Case
