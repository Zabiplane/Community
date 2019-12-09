# Zabiplane History

Just a bit of background as to how we got where we are today.

## Origin Story, 2019

_(no, there's no spider bite involved)_

People at Juniper Networks, Red Hat, and Intel all noticed a similar problem: data plane fragmentation. This was causing each company to fracture its efforts across data plane and control plane. Wouldn't it be much better if the data plane were in or near the kernel and shipped by default with every Linux? If everyone were using a standard, secure, fast, and easy to use data plane? If everyone could then focus their efforts on the real differentiator, the control plane?

After talking it through, these companies all agreed that not only was this a great idea, but that it would finally be possible using [eBPF](http://www.brendangregg.com/blog/2019-01-01/learn-ebpf-tracing.html) and [XDP](https://prototype-kernel.readthedocs.io/en/latest/networking/XDP/). They all agreed that the project should be as open as possible by default, but to keep the initial development manageable they'd keep the community small at first (avoid the "too many cooks in the kitchen" problem). 

In October 2019, the community came together at the Red Hat office in Sunnyvale for the first summit. Representatives from Red Hat, Intel, Juniper, and VMware worked for two days to discuss a rough vision for the project, including gathering initial use cases and forming working groups.

After this summit, the working groups started meeting regularly to make progress on use cases, a comparative matrix of other data planes, R&D, and other matters. The entire community came together for its first virtual conference (conference call) in December 2019 for all working groups to share what they'd learned so far. During this call they decided not only that there'd be another virtual conference in January but also that they'd all come together for the second summit in February 2020.

## About the name

Because the project was about data planes and was probably going to lean heavily on eBPF, when the project started a working title of `ebplane` was used until a real name could be chosen. You may still find references to `ebplane` in the earliest project docs.

In December 2019, after an extensive process that included an outside naming firm and lawyers reviewing for possible trademark collisions, the community voted and chose the final name `Zabiplane` for the project. The reason for the `-plane` part of that is obvious; the `Zabi-` less so. It means "antelope" in Arabic (ظبي) and is meant to evoke the speed the data plane will have.
