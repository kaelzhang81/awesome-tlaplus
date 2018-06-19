# awesome-tlaplus

TLA+ is a formal specification and verification language to help engineers design, specify, reason about, and verify complex software and hardware systems. It is widely used to verify the algorithms in distributed systems.

## WebSite

* homepage : https://lamport.azurewebsites.net/tla/tla.html

## TLA+ Cases


| name | description |  
| --- | --- | 
| [Batch Installer (H)](https://medium.com/espark-engineering-blog/formal-methods-in-practice-8f20d72bce4f) | Sending async batches of commands. |
| [Redux (H)](https://www.hillelwayne.com/post/tla-redux/) | Redux reducers with verifying a temporal property. |
| [Zero Downtime Deployments (H)](https://www.hillelwayne.com/post/modeling-deployments/) | A simple model of a deploying new code to servers where at least one server is always available to clients, and all available servers show the same code version. |
| [Trading Algorithm](https://www.linkedin.com/pulse/lamports-tla-spec-testing-why-youre-using-nira-amit/) | Trading boths executing trades in a simulated market, showing how it’s susceptible to flash crashes. |
| [Detecting Linked-List Cycles](https://lorinhochstein.wordpress.com/2017/10/16/the-tortoise-and-the-hare-in-tla/) | Finding cycles in linked lists. |
| [Replicated Storage](http://muratbuffalo.blogspot.com/2016/11/modeling-replicated-storage-system-in.html) | Replicated storage system with a quorum. |
| [Rate Limiter (H)](https://learntla.com/concurrency/example/) | Independent workers hitting a rate-limited API. |
| [Thread Pool (T)](http://www.cs.unh.edu/~charpov/programming-tlabuffer.html) | Multiple reader and writer threads sharing a bounded queue, discovering deadlocks. |
| [Bank Transfer (H)](https://learntla.com/introduction/example/) | Specifying a bank transfer with overdraft protection. |
| [Finding bugs in systems through formalization](https://andy.hammerhartes.de/finding-bugs-in-systems-through-formalization.html) | Ensuring distributed jobs go from “pending” to “completed”. |
|  |  |

## TLA+ Video Resources

* [Debugging software designs using testable pseudo-code (TLA+)](https://www.youtube.com/watch?v=LAEXHua4MQQ)

## TLA+ Example

* allocator
   Specification of a resource allocator, written by Stephan Merz.

* [CarTalkPuzzle](https://github.com/kaelzhang81/Examples/tree/master/specifications/CarTalkPuzzle)
   A TLA+ specification of the solution to a nice puzzle.

* chang_roberts
   A PlusCal specification of the algorithm by Chang and Roberts (1979) for electing a leader on a unidirectional ring.

* [DieHard](https://github.com/kaelzhang81/Examples/tree/master/specifications/DieHard)
   A very elementary example based on a puzzle from a movie.
   It provides a good first introduction to TLA+.

* dijkstra-mutex
   A PlusCal version of the first published mutual exclusion algorithm, written by Edsger Dijkstra.

* ewd840
   A TLA+ specification of an algorithm due to Dijkstra, Feijen, and van Gasteren for detecting distributed termination on a unidirectional ring, together with a safety proof.

* lamport_mutex
   A TLA+ specification of the distributed mutual-exclusion algorithm that appeared as an example in Lamport's classic paper "Time, Clocks and the Ordering of Events in a  Distributed System", together with a hierarchical proof of mutual exclusion.

* [N-Queens](https://github.com/kaelzhang81/Examples/tree/master/specifications/N-Queens)
   TLA+ and PlusCal descriptions of a solution to the N queens problem.  Written by Stephan Merz.
   
* [Paxos](https://github.com/kaelzhang81/Examples/tree/master/specifications/Paxos)
   A high-level specification of the Paxos consensus algorithm, consisting of a specification of consensus, a very high level spec of the algorithm (with no messages) that implements consensus and is implemented by the Paxos algorithm.  

* [Prisoners](https://github.com/kaelzhang81/Examples/tree/master/specifications/Prisoners)
   A simple specification that solves a puzzle that was presented on an American radio program.  The solution is rather subtle, and hence it's not so easy to understand why the solution is correct.
      
* [Specifying Systems](https://github.com/kaelzhang81/Examples/tree/master/specifications/SpecifyingSystems)
  Examples to accompany the book Specifying Systems.
 
* [Stones](https://github.com/kaelzhang81/Examples/tree/master/specifications/Stones)
   Another specification that solves the same proble as CarTalkPuzzle.

* [sums_even](https://github.com/kaelzhang81/Examples/tree/master/specifications/sums_even)
   Two proofs for showing that x+x is even, for any natural number x.

* [tower_of_hanoi](https://github.com/kaelzhang81/Examples/tree/master/specifications/tower_of_hanoi)
   The well-known Towers of Hanoi puzzle.

* [transaction_commit](https://github.com/kaelzhang81/Examples/tree/master/specifications/transaction_commit)
   TLA+ specifications underlying the paper "Consensus on Transaction Commit" by Gray and Lamport (2006).

* [TransitiveClosure](https://github.com/kaelzhang81/Examples/tree/master/specifications/TransitiveClosure)
   Someone once posted on TLAPlus.net a question asking how the transitive closure of a relation can be defined in TLA+. This answers the question by giving several equivalent definitions.  Reading them might help you when you have to define some mathematical operation that requires a recursive definition.

* [TwoPhase](https://github.com/kaelzhang81/Examples/tree/master/specifications/TwoPhase)
   A specification of a very simple hardware protocol and of the problem it solves.  This is a nice example of the use of instantiation to describe a refinement mapping, and of the use of constant operator parameters to describe unspecified actions.  There is also a TLA+ proof of correctness that has been checked by the TLAPS proof system.























