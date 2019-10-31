# NetFragmentIteratorGetCount method


## Description



The **NetFragmentIteratorGetCount** method gets the count of fragments that a client driver owns in the fragment ring.

## Parameters

### Iterator

A pointer to a [**NET_RING_FRAGMENT_ITERATOR**](net_ring_fragment_iterator.md) structure.

## Returns

Returns the number of fragments between this fragment iterator's current **Index** and **EndIndex - 1** inclusive. For example, if the iterator's **Index** is **1** and its **End** index is **5**, the client driver owns four fragments: **1**, **2**, **3**, and **4**.

## See Also

[Net ring iterator README](readme.md)

[**NET_RING_FRAGMENT_ITERATOR**](net_ring_fragment_iterator.md)