If you're not familiar with what a "service mesh" is, read what [William Morgan](https://twitter.com/wm), one of the creators of Linkerd, the project that gave birth to the term service mesh, has to [say about it](https://servicemesh.io/):

> For all the hype, the service mesh is architecturally pretty straightforward. It’s nothing more than a bunch of userspace proxies, stuck “next” to your services [...], plus a set of management processes. The proxies are referred to as the service mesh’s data plane, and the management processes as its control plane. The data plane intercepts calls between services and “does stuff” with these calls; the control plane coordinates the behavior of the proxies, and provides an API for you, the operator, to manipulate and measure the mesh as a whole.

No matter what [flavor of service mesh](https://servicemesh.es/) you prefer, be it CNCF Envoy ([Matt Klein](https://blog.envoyproxy.io/@mattklein123) of Lyft gave birth to that one), or CNCF Linkerd, or the new kid in town, Microsoft's [Open Service Mesh](https://openservicemesh.io/), you likely will benefit from a service mesh across a number of [use cases](https://lucperkins.dev/blog/service-mesh-use-cases/).

We believe:

1. Service meshes are good and here to stay.
2. Service meshes should work across compute.
3. Using service meshes should be easy, and
4. Conversely, their cognitive & technical overhead should be minimal.
