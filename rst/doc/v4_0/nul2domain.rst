.. _nul2domain:

nul2domain
===========================================

.. class:: nul2domain.NUL2Domain(bambou.nurest_object.NUMetaRESTObject,):

This is the definition of a l2 domain associated with a Enterprise.


Attributes
----------


- ``dhcp_managed``: decides whether L2Domain / L2Domain template DHCP is managed by VSD

- ``dpi``: determines whether or not Deep packet inspection is enabled

- ``ip_type``: IPv4 or IPv6

- ``maintenance_mode``: maintenanceMode is an enum that indicates if the L2Domain is accepting VM activation requests. Possible values are DISABLED, ENABLED and ENABLED_INHERITED Possible values are .

- ``name`` (**Mandatory**): Name of the L2Domain / L2Domain template,has to be unique within a Enterprise. Valid characters are alphabets, numbers, space and hyphen( - ).

- ``last_updated_by``: ID of the user who last updated the object.

- ``gateway``: The IP address of the gateway of this l2 domain

- ``gateway_mac_address``: The MAC address of the Gateway.

- ``address``: Network address of the L2Domain / L2Domain template defined. 

- ``template_id``: The ID of the L2 Domain template that this L2 Domain object was derived from

- ``service_id``: The service ID used by the VSCs to identify this subnet

- ``description``: A description field provided by the user that identifies the L2Domain / L2Domain template.

- ``netmask``: Netmask of the L2Domain / L2Domain template defined

- ``vn_id``: Current Network's  globally unique  VXLAN network identifier generated by VSD

- ``encryption``: Determines whether IPSEC is enabled Possible values are ENABLED, DISABLED, .

- ``entity_scope``: Specify if scope of entity is Data center or Enterprise level

- ``policy_change_status``: None

- ``route_distinguisher``: The Route Distinguisher value assigned by VSD for this subnet that is used by the BGP-EVPN protocol in VSC

- ``route_target``: The Route Target value assigned by VSD for this subnet that is used by the BGP-EVPN protocol in VSC

- ``uplink_preference``: Indicates the preferencial path selection for network traffic in this domain - Default is Primary 1 and Secondary 2. Possible values are PRIMARY_SECONDARY, SECONDARY_PRIMARY, PRIMARY, SECONDARY, SYMMETRIC, .

- ``associated_multicast_channel_map_id``: The ID of the Multi Cast Channel Map this L2Domain / L2Domain template template is associated with. This has to be set when  enableMultiCast is set to ENABLED

- ``associated_shared_network_resource_id``: The ID of the L2 Domain  that this L2 Domain object is pointing to

- ``stretched``: Indicates whether this domain is streched,if so remote VM resolutions will be allowed

- ``multicast``: Indicates multicast policy on L2Domain.

- ``external_id``: External object ID. Used for integration with third party systems




Children
--------

================================================================================================================================================               ==========================================================================================
**class**                                                                                                                                                      **fetcher**

:ref:`nutca.NUTCA<nutca>`                                                                                                                                        ``tcas`` 
:ref:`nuaddressrange.NUAddressRange<nuaddressrange>`                                                                                                             ``address_ranges`` 
:ref:`nuredirectiontarget.NURedirectionTarget<nuredirectiontarget>`                                                                                              ``redirection_targets`` 
:ref:`nupermission.NUPermission<nupermission>`                                                                                                                   ``permissions`` 
:ref:`numetadata.NUMetadata<numetadata>`                                                                                                                         ``metadatas`` 
:ref:`nuegressaclentrytemplate.NUEgressACLEntryTemplate<nuegressaclentrytemplate>`                                                                               ``egress_acl_entry_templates`` 
:ref:`nuegressacltemplate.NUEgressACLTemplate<nuegressacltemplate>`                                                                                              ``egress_acl_templates`` 
:ref:`nudhcpoption.NUDHCPOption<nudhcpoption>`                                                                                                                   ``dhcp_options`` 
:ref:`nuglobalmetadata.NUGlobalMetadata<nuglobalmetadata>`                                                                                                       ``global_metadatas`` 
:ref:`nuvm.NUVM<nuvm>`                                                                                                                                           ``vms`` 
:ref:`nuvminterface.NUVMInterface<nuvminterface>`                                                                                                                ``vm_interfaces`` 
:ref:`nuingressaclentrytemplate.NUIngressACLEntryTemplate<nuingressaclentrytemplate>`                                                                            ``ingress_acl_entry_templates`` 
:ref:`nuingressacltemplate.NUIngressACLTemplate<nuingressacltemplate>`                                                                                           ``ingress_acl_templates`` 
:ref:`nuingressadvfwdtemplate.NUIngressAdvFwdTemplate<nuingressadvfwdtemplate>`                                                                                  ``ingress_adv_fwd_templates`` 
:ref:`nuingressexternalservicetemplate.NUIngressExternalServiceTemplate<nuingressexternalservicetemplate>`                                                       ``ingress_external_service_templates`` 
:ref:`nujob.NUJob<nujob>`                                                                                                                                        ``jobs`` 
:ref:`nupolicygroup.NUPolicyGroup<nupolicygroup>`                                                                                                                ``policy_groups`` 
:ref:`nucontainer.NUContainer<nucontainer>`                                                                                                                      ``containers`` 
:ref:`nucontainerinterface.NUContainerInterface<nucontainerinterface>`                                                                                           ``container_interfaces`` 
:ref:`nuqos.NUQOS<nuqos>`                                                                                                                                        ``qoss`` 
:ref:`nuhostinterface.NUHostInterface<nuhostinterface>`                                                                                                          ``host_interfaces`` 
:ref:`nuuplinkrd.NUUplinkRD<nuuplinkrd>`                                                                                                                         ``uplink_rds`` 
:ref:`nuvpnconnection.NUVPNConnection<nuvpnconnection>`                                                                                                          ``vpn_connections`` 
:ref:`nuvport.NUVPort<nuvport>`                                                                                                                                  ``vports`` 
:ref:`nuapplicationperformancemanagementbinding.NUApplicationperformancemanagementbinding<nuapplicationperformancemanagementbinding>`                            ``applicationperformancemanagementbindings`` 
:ref:`nubridgeinterface.NUBridgeInterface<nubridgeinterface>`                                                                                                    ``bridge_interfaces`` 
:ref:`nugroup.NUGroup<nugroup>`                                                                                                                                  ``groups`` 
:ref:`nustaticroute.NUStaticRoute<nustaticroute>`                                                                                                                ``static_routes`` 
:ref:`nustatistics.NUStatistics<nustatistics>`                                                                                                                   ``statistics`` 
:ref:`nustatisticspolicy.NUStatisticsPolicy<nustatisticspolicy>`                                                                                                 ``statistics_policies`` 
:ref:`nueventlog.NUEventLog<nueventlog>`                                                                                                                         ``event_logs`` 
================================================================================================================================================               ==========================================================================================



Parents
--------


- :ref:`nul2domaintemplate.NUL2DomainTemplate<nul2domaintemplate>`

- :ref:`nume.NUMe<nume>`

- :ref:`nuenterprise.NUEnterprise<nuenterprise>`

