<h1>Virtualization</h1>

<p>It is the techinque of splitting a physical resource into as many logical resources as we want as example- cpu, memory </p>

<p>Virtualization is technology that transform physical resources (hardware)to logical resources(software).</p>

******************

<p>Virtualization can be both types spliting resource into multiple resources and merging multiple resources to one resources. </p>

![SPliting resource to multiple resources](./images/splitingResources.png) ![SPliting resource to multiple resources](./images/mergingResources.png) 

*****************
<h3>A general overview of virtualization :</h3>

![Virtualization Overview](./images/virtualization.png)

<p>Here all the VM are isolated from each other.</p>

<p>Hypervisor is a virtualization software. It vitualize the physical resources.</p>

*****************

<h3>Hypervisor</h3>

<p>Hypervisor is a piece of software or firmware that creates and run virtual machine.A hypervisor is sometimes also called a <b>virtual machine manager (VMM)</b></p>

<h4>Types of hypervisor</h4>

![Types of Hypervisor](./images/typesOfHypervisor.drawio.png)

<h4>Type-1 Hypervisor(firmware)</h4>

<p>Also called Bare metal hypervisor. Type-1 Hypervisor run directly on the system hardware. A guest OS run on another level above the hypervisor.</p>


<ul>

<li> VMware ESXi is a type-1 hypervisor that runs on the host server hardware without an underlying OS.</li>

<li>Type-1 hypervisor act as their own operating system.</li>


</ul>

<p>ESXi provides  a virtualization layer that abstracts the cpu, storage, memory and networking resources of the physical host into multiple virtual machine.</p>

![Type-1 hypervisor](./images/virtualization.png)

<h5>Type-2 Hypervisor</h5>

<p>Hypervisor that runs within a convention OS environment and the host OS provides.</p>

<ul>

<li>Example of Type-2 hypervisor are Vmware workstation, Oracle Virtual Box and Microsoft Virtual Pc.</li>

<li>It does not have direct access to the host hardware and resources.</li>

</ul>

![Type-2 hypervisor](./images/type-2Hypervisor.drawio.png)

