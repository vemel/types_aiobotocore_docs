<a id="ec2client-for-aiobotocore-ec2-module"></a>

# EC2Client for aiobotocore EC2 module

> [Index](..) > [EC2](.) > EC2Client

Auto-generated documentation for
[EC2](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2)
type annotations stubs module
[types-aiobotocore-ec2](https://pypi.org/project/types-aiobotocore-ec2/).

- [EC2Client for aiobotocore EC2 module](#ec2client-for-aiobotocore-ec2-module)
  - [EC2Client](#ec2client)
  - [Exceptions](#exceptions)
  - [Methods](#methods)
    - [exceptions](#exceptions)
    - [accept_reserved_instances_exchange_quote](#accept_reserved_instances_exchange_quote)
    - [accept_transit_gateway_multicast_domain_associations](#accept_transit_gateway_multicast_domain_associations)
    - [accept_transit_gateway_peering_attachment](#accept_transit_gateway_peering_attachment)
    - [accept_transit_gateway_vpc_attachment](#accept_transit_gateway_vpc_attachment)
    - [accept_vpc_endpoint_connections](#accept_vpc_endpoint_connections)
    - [accept_vpc_peering_connection](#accept_vpc_peering_connection)
    - [advertise_byoip_cidr](#advertise_byoip_cidr)
    - [allocate_address](#allocate_address)
    - [allocate_hosts](#allocate_hosts)
    - [allocate_ipam_pool_cidr](#allocate_ipam_pool_cidr)
    - [apply_security_groups_to_client_vpn_target_network](#apply_security_groups_to_client_vpn_target_network)
    - [assign_ipv6_addresses](#assign_ipv6_addresses)
    - [assign_private_ip_addresses](#assign_private_ip_addresses)
    - [associate_address](#associate_address)
    - [associate_client_vpn_target_network](#associate_client_vpn_target_network)
    - [associate_dhcp_options](#associate_dhcp_options)
    - [associate_enclave_certificate_iam_role](#associate_enclave_certificate_iam_role)
    - [associate_iam_instance_profile](#associate_iam_instance_profile)
    - [associate_instance_event_window](#associate_instance_event_window)
    - [associate_route_table](#associate_route_table)
    - [associate_subnet_cidr_block](#associate_subnet_cidr_block)
    - [associate_transit_gateway_multicast_domain](#associate_transit_gateway_multicast_domain)
    - [associate_transit_gateway_route_table](#associate_transit_gateway_route_table)
    - [associate_trunk_interface](#associate_trunk_interface)
    - [associate_vpc_cidr_block](#associate_vpc_cidr_block)
    - [attach_classic_link_vpc](#attach_classic_link_vpc)
    - [attach_internet_gateway](#attach_internet_gateway)
    - [attach_network_interface](#attach_network_interface)
    - [attach_volume](#attach_volume)
    - [attach_vpn_gateway](#attach_vpn_gateway)
    - [authorize_client_vpn_ingress](#authorize_client_vpn_ingress)
    - [authorize_security_group_egress](#authorize_security_group_egress)
    - [authorize_security_group_ingress](#authorize_security_group_ingress)
    - [bundle_instance](#bundle_instance)
    - [can_paginate](#can_paginate)
    - [cancel_bundle_task](#cancel_bundle_task)
    - [cancel_capacity_reservation](#cancel_capacity_reservation)
    - [cancel_capacity_reservation_fleets](#cancel_capacity_reservation_fleets)
    - [cancel_conversion_task](#cancel_conversion_task)
    - [cancel_export_task](#cancel_export_task)
    - [cancel_import_task](#cancel_import_task)
    - [cancel_reserved_instances_listing](#cancel_reserved_instances_listing)
    - [cancel_spot_fleet_requests](#cancel_spot_fleet_requests)
    - [cancel_spot_instance_requests](#cancel_spot_instance_requests)
    - [confirm_product_instance](#confirm_product_instance)
    - [copy_fpga_image](#copy_fpga_image)
    - [copy_image](#copy_image)
    - [copy_snapshot](#copy_snapshot)
    - [create_capacity_reservation](#create_capacity_reservation)
    - [create_capacity_reservation_fleet](#create_capacity_reservation_fleet)
    - [create_carrier_gateway](#create_carrier_gateway)
    - [create_client_vpn_endpoint](#create_client_vpn_endpoint)
    - [create_client_vpn_route](#create_client_vpn_route)
    - [create_customer_gateway](#create_customer_gateway)
    - [create_default_subnet](#create_default_subnet)
    - [create_default_vpc](#create_default_vpc)
    - [create_dhcp_options](#create_dhcp_options)
    - [create_egress_only_internet_gateway](#create_egress_only_internet_gateway)
    - [create_fleet](#create_fleet)
    - [create_flow_logs](#create_flow_logs)
    - [create_fpga_image](#create_fpga_image)
    - [create_image](#create_image)
    - [create_instance_event_window](#create_instance_event_window)
    - [create_instance_export_task](#create_instance_export_task)
    - [create_internet_gateway](#create_internet_gateway)
    - [create_ipam](#create_ipam)
    - [create_ipam_pool](#create_ipam_pool)
    - [create_ipam_scope](#create_ipam_scope)
    - [create_key_pair](#create_key_pair)
    - [create_launch_template](#create_launch_template)
    - [create_launch_template_version](#create_launch_template_version)
    - [create_local_gateway_route](#create_local_gateway_route)
    - [create_local_gateway_route_table_vpc_association](#create_local_gateway_route_table_vpc_association)
    - [create_managed_prefix_list](#create_managed_prefix_list)
    - [create_nat_gateway](#create_nat_gateway)
    - [create_network_acl](#create_network_acl)
    - [create_network_acl_entry](#create_network_acl_entry)
    - [create_network_insights_access_scope](#create_network_insights_access_scope)
    - [create_network_insights_path](#create_network_insights_path)
    - [create_network_interface](#create_network_interface)
    - [create_network_interface_permission](#create_network_interface_permission)
    - [create_placement_group](#create_placement_group)
    - [create_public_ipv4_pool](#create_public_ipv4_pool)
    - [create_replace_root_volume_task](#create_replace_root_volume_task)
    - [create_reserved_instances_listing](#create_reserved_instances_listing)
    - [create_restore_image_task](#create_restore_image_task)
    - [create_route](#create_route)
    - [create_route_table](#create_route_table)
    - [create_security_group](#create_security_group)
    - [create_snapshot](#create_snapshot)
    - [create_snapshots](#create_snapshots)
    - [create_spot_datafeed_subscription](#create_spot_datafeed_subscription)
    - [create_store_image_task](#create_store_image_task)
    - [create_subnet](#create_subnet)
    - [create_subnet_cidr_reservation](#create_subnet_cidr_reservation)
    - [create_tags](#create_tags)
    - [create_traffic_mirror_filter](#create_traffic_mirror_filter)
    - [create_traffic_mirror_filter_rule](#create_traffic_mirror_filter_rule)
    - [create_traffic_mirror_session](#create_traffic_mirror_session)
    - [create_traffic_mirror_target](#create_traffic_mirror_target)
    - [create_transit_gateway](#create_transit_gateway)
    - [create_transit_gateway_connect](#create_transit_gateway_connect)
    - [create_transit_gateway_connect_peer](#create_transit_gateway_connect_peer)
    - [create_transit_gateway_multicast_domain](#create_transit_gateway_multicast_domain)
    - [create_transit_gateway_peering_attachment](#create_transit_gateway_peering_attachment)
    - [create_transit_gateway_prefix_list_reference](#create_transit_gateway_prefix_list_reference)
    - [create_transit_gateway_route](#create_transit_gateway_route)
    - [create_transit_gateway_route_table](#create_transit_gateway_route_table)
    - [create_transit_gateway_vpc_attachment](#create_transit_gateway_vpc_attachment)
    - [create_volume](#create_volume)
    - [create_vpc](#create_vpc)
    - [create_vpc_endpoint](#create_vpc_endpoint)
    - [create_vpc_endpoint_connection_notification](#create_vpc_endpoint_connection_notification)
    - [create_vpc_endpoint_service_configuration](#create_vpc_endpoint_service_configuration)
    - [create_vpc_peering_connection](#create_vpc_peering_connection)
    - [create_vpn_connection](#create_vpn_connection)
    - [create_vpn_connection_route](#create_vpn_connection_route)
    - [create_vpn_gateway](#create_vpn_gateway)
    - [delete_carrier_gateway](#delete_carrier_gateway)
    - [delete_client_vpn_endpoint](#delete_client_vpn_endpoint)
    - [delete_client_vpn_route](#delete_client_vpn_route)
    - [delete_customer_gateway](#delete_customer_gateway)
    - [delete_dhcp_options](#delete_dhcp_options)
    - [delete_egress_only_internet_gateway](#delete_egress_only_internet_gateway)
    - [delete_fleets](#delete_fleets)
    - [delete_flow_logs](#delete_flow_logs)
    - [delete_fpga_image](#delete_fpga_image)
    - [delete_instance_event_window](#delete_instance_event_window)
    - [delete_internet_gateway](#delete_internet_gateway)
    - [delete_ipam](#delete_ipam)
    - [delete_ipam_pool](#delete_ipam_pool)
    - [delete_ipam_scope](#delete_ipam_scope)
    - [delete_key_pair](#delete_key_pair)
    - [delete_launch_template](#delete_launch_template)
    - [delete_launch_template_versions](#delete_launch_template_versions)
    - [delete_local_gateway_route](#delete_local_gateway_route)
    - [delete_local_gateway_route_table_vpc_association](#delete_local_gateway_route_table_vpc_association)
    - [delete_managed_prefix_list](#delete_managed_prefix_list)
    - [delete_nat_gateway](#delete_nat_gateway)
    - [delete_network_acl](#delete_network_acl)
    - [delete_network_acl_entry](#delete_network_acl_entry)
    - [delete_network_insights_access_scope](#delete_network_insights_access_scope)
    - [delete_network_insights_access_scope_analysis](#delete_network_insights_access_scope_analysis)
    - [delete_network_insights_analysis](#delete_network_insights_analysis)
    - [delete_network_insights_path](#delete_network_insights_path)
    - [delete_network_interface](#delete_network_interface)
    - [delete_network_interface_permission](#delete_network_interface_permission)
    - [delete_placement_group](#delete_placement_group)
    - [delete_public_ipv4_pool](#delete_public_ipv4_pool)
    - [delete_queued_reserved_instances](#delete_queued_reserved_instances)
    - [delete_route](#delete_route)
    - [delete_route_table](#delete_route_table)
    - [delete_security_group](#delete_security_group)
    - [delete_snapshot](#delete_snapshot)
    - [delete_spot_datafeed_subscription](#delete_spot_datafeed_subscription)
    - [delete_subnet](#delete_subnet)
    - [delete_subnet_cidr_reservation](#delete_subnet_cidr_reservation)
    - [delete_tags](#delete_tags)
    - [delete_traffic_mirror_filter](#delete_traffic_mirror_filter)
    - [delete_traffic_mirror_filter_rule](#delete_traffic_mirror_filter_rule)
    - [delete_traffic_mirror_session](#delete_traffic_mirror_session)
    - [delete_traffic_mirror_target](#delete_traffic_mirror_target)
    - [delete_transit_gateway](#delete_transit_gateway)
    - [delete_transit_gateway_connect](#delete_transit_gateway_connect)
    - [delete_transit_gateway_connect_peer](#delete_transit_gateway_connect_peer)
    - [delete_transit_gateway_multicast_domain](#delete_transit_gateway_multicast_domain)
    - [delete_transit_gateway_peering_attachment](#delete_transit_gateway_peering_attachment)
    - [delete_transit_gateway_prefix_list_reference](#delete_transit_gateway_prefix_list_reference)
    - [delete_transit_gateway_route](#delete_transit_gateway_route)
    - [delete_transit_gateway_route_table](#delete_transit_gateway_route_table)
    - [delete_transit_gateway_vpc_attachment](#delete_transit_gateway_vpc_attachment)
    - [delete_volume](#delete_volume)
    - [delete_vpc](#delete_vpc)
    - [delete_vpc_endpoint_connection_notifications](#delete_vpc_endpoint_connection_notifications)
    - [delete_vpc_endpoint_service_configurations](#delete_vpc_endpoint_service_configurations)
    - [delete_vpc_endpoints](#delete_vpc_endpoints)
    - [delete_vpc_peering_connection](#delete_vpc_peering_connection)
    - [delete_vpn_connection](#delete_vpn_connection)
    - [delete_vpn_connection_route](#delete_vpn_connection_route)
    - [delete_vpn_gateway](#delete_vpn_gateway)
    - [deprovision_byoip_cidr](#deprovision_byoip_cidr)
    - [deprovision_ipam_pool_cidr](#deprovision_ipam_pool_cidr)
    - [deprovision_public_ipv4_pool_cidr](#deprovision_public_ipv4_pool_cidr)
    - [deregister_image](#deregister_image)
    - [deregister_instance_event_notification_attributes](#deregister_instance_event_notification_attributes)
    - [deregister_transit_gateway_multicast_group_members](#deregister_transit_gateway_multicast_group_members)
    - [deregister_transit_gateway_multicast_group_sources](#deregister_transit_gateway_multicast_group_sources)
    - [describe_account_attributes](#describe_account_attributes)
    - [describe_addresses](#describe_addresses)
    - [describe_addresses_attribute](#describe_addresses_attribute)
    - [describe_aggregate_id_format](#describe_aggregate_id_format)
    - [describe_availability_zones](#describe_availability_zones)
    - [describe_bundle_tasks](#describe_bundle_tasks)
    - [describe_byoip_cidrs](#describe_byoip_cidrs)
    - [describe_capacity_reservation_fleets](#describe_capacity_reservation_fleets)
    - [describe_capacity_reservations](#describe_capacity_reservations)
    - [describe_carrier_gateways](#describe_carrier_gateways)
    - [describe_classic_link_instances](#describe_classic_link_instances)
    - [describe_client_vpn_authorization_rules](#describe_client_vpn_authorization_rules)
    - [describe_client_vpn_connections](#describe_client_vpn_connections)
    - [describe_client_vpn_endpoints](#describe_client_vpn_endpoints)
    - [describe_client_vpn_routes](#describe_client_vpn_routes)
    - [describe_client_vpn_target_networks](#describe_client_vpn_target_networks)
    - [describe_coip_pools](#describe_coip_pools)
    - [describe_conversion_tasks](#describe_conversion_tasks)
    - [describe_customer_gateways](#describe_customer_gateways)
    - [describe_dhcp_options](#describe_dhcp_options)
    - [describe_egress_only_internet_gateways](#describe_egress_only_internet_gateways)
    - [describe_elastic_gpus](#describe_elastic_gpus)
    - [describe_export_image_tasks](#describe_export_image_tasks)
    - [describe_export_tasks](#describe_export_tasks)
    - [describe_fast_snapshot_restores](#describe_fast_snapshot_restores)
    - [describe_fleet_history](#describe_fleet_history)
    - [describe_fleet_instances](#describe_fleet_instances)
    - [describe_fleets](#describe_fleets)
    - [describe_flow_logs](#describe_flow_logs)
    - [describe_fpga_image_attribute](#describe_fpga_image_attribute)
    - [describe_fpga_images](#describe_fpga_images)
    - [describe_host_reservation_offerings](#describe_host_reservation_offerings)
    - [describe_host_reservations](#describe_host_reservations)
    - [describe_hosts](#describe_hosts)
    - [describe_iam_instance_profile_associations](#describe_iam_instance_profile_associations)
    - [describe_id_format](#describe_id_format)
    - [describe_identity_id_format](#describe_identity_id_format)
    - [describe_image_attribute](#describe_image_attribute)
    - [describe_images](#describe_images)
    - [describe_import_image_tasks](#describe_import_image_tasks)
    - [describe_import_snapshot_tasks](#describe_import_snapshot_tasks)
    - [describe_instance_attribute](#describe_instance_attribute)
    - [describe_instance_credit_specifications](#describe_instance_credit_specifications)
    - [describe_instance_event_notification_attributes](#describe_instance_event_notification_attributes)
    - [describe_instance_event_windows](#describe_instance_event_windows)
    - [describe_instance_status](#describe_instance_status)
    - [describe_instance_type_offerings](#describe_instance_type_offerings)
    - [describe_instance_types](#describe_instance_types)
    - [describe_instances](#describe_instances)
    - [describe_internet_gateways](#describe_internet_gateways)
    - [describe_ipam_pools](#describe_ipam_pools)
    - [describe_ipam_scopes](#describe_ipam_scopes)
    - [describe_ipams](#describe_ipams)
    - [describe_ipv6_pools](#describe_ipv6_pools)
    - [describe_key_pairs](#describe_key_pairs)
    - [describe_launch_template_versions](#describe_launch_template_versions)
    - [describe_launch_templates](#describe_launch_templates)
    - [describe_local_gateway_route_table_virtual_interface_group_associations](#describe_local_gateway_route_table_virtual_interface_group_associations)
    - [describe_local_gateway_route_table_vpc_associations](#describe_local_gateway_route_table_vpc_associations)
    - [describe_local_gateway_route_tables](#describe_local_gateway_route_tables)
    - [describe_local_gateway_virtual_interface_groups](#describe_local_gateway_virtual_interface_groups)
    - [describe_local_gateway_virtual_interfaces](#describe_local_gateway_virtual_interfaces)
    - [describe_local_gateways](#describe_local_gateways)
    - [describe_managed_prefix_lists](#describe_managed_prefix_lists)
    - [describe_moving_addresses](#describe_moving_addresses)
    - [describe_nat_gateways](#describe_nat_gateways)
    - [describe_network_acls](#describe_network_acls)
    - [describe_network_insights_access_scope_analyses](#describe_network_insights_access_scope_analyses)
    - [describe_network_insights_access_scopes](#describe_network_insights_access_scopes)
    - [describe_network_insights_analyses](#describe_network_insights_analyses)
    - [describe_network_insights_paths](#describe_network_insights_paths)
    - [describe_network_interface_attribute](#describe_network_interface_attribute)
    - [describe_network_interface_permissions](#describe_network_interface_permissions)
    - [describe_network_interfaces](#describe_network_interfaces)
    - [describe_placement_groups](#describe_placement_groups)
    - [describe_prefix_lists](#describe_prefix_lists)
    - [describe_principal_id_format](#describe_principal_id_format)
    - [describe_public_ipv4_pools](#describe_public_ipv4_pools)
    - [describe_regions](#describe_regions)
    - [describe_replace_root_volume_tasks](#describe_replace_root_volume_tasks)
    - [describe_reserved_instances](#describe_reserved_instances)
    - [describe_reserved_instances_listings](#describe_reserved_instances_listings)
    - [describe_reserved_instances_modifications](#describe_reserved_instances_modifications)
    - [describe_reserved_instances_offerings](#describe_reserved_instances_offerings)
    - [describe_route_tables](#describe_route_tables)
    - [describe_scheduled_instance_availability](#describe_scheduled_instance_availability)
    - [describe_scheduled_instances](#describe_scheduled_instances)
    - [describe_security_group_references](#describe_security_group_references)
    - [describe_security_group_rules](#describe_security_group_rules)
    - [describe_security_groups](#describe_security_groups)
    - [describe_snapshot_attribute](#describe_snapshot_attribute)
    - [describe_snapshot_tier_status](#describe_snapshot_tier_status)
    - [describe_snapshots](#describe_snapshots)
    - [describe_spot_datafeed_subscription](#describe_spot_datafeed_subscription)
    - [describe_spot_fleet_instances](#describe_spot_fleet_instances)
    - [describe_spot_fleet_request_history](#describe_spot_fleet_request_history)
    - [describe_spot_fleet_requests](#describe_spot_fleet_requests)
    - [describe_spot_instance_requests](#describe_spot_instance_requests)
    - [describe_spot_price_history](#describe_spot_price_history)
    - [describe_stale_security_groups](#describe_stale_security_groups)
    - [describe_store_image_tasks](#describe_store_image_tasks)
    - [describe_subnets](#describe_subnets)
    - [describe_tags](#describe_tags)
    - [describe_traffic_mirror_filters](#describe_traffic_mirror_filters)
    - [describe_traffic_mirror_sessions](#describe_traffic_mirror_sessions)
    - [describe_traffic_mirror_targets](#describe_traffic_mirror_targets)
    - [describe_transit_gateway_attachments](#describe_transit_gateway_attachments)
    - [describe_transit_gateway_connect_peers](#describe_transit_gateway_connect_peers)
    - [describe_transit_gateway_connects](#describe_transit_gateway_connects)
    - [describe_transit_gateway_multicast_domains](#describe_transit_gateway_multicast_domains)
    - [describe_transit_gateway_peering_attachments](#describe_transit_gateway_peering_attachments)
    - [describe_transit_gateway_route_tables](#describe_transit_gateway_route_tables)
    - [describe_transit_gateway_vpc_attachments](#describe_transit_gateway_vpc_attachments)
    - [describe_transit_gateways](#describe_transit_gateways)
    - [describe_trunk_interface_associations](#describe_trunk_interface_associations)
    - [describe_volume_attribute](#describe_volume_attribute)
    - [describe_volume_status](#describe_volume_status)
    - [describe_volumes](#describe_volumes)
    - [describe_volumes_modifications](#describe_volumes_modifications)
    - [describe_vpc_attribute](#describe_vpc_attribute)
    - [describe_vpc_classic_link](#describe_vpc_classic_link)
    - [describe_vpc_classic_link_dns_support](#describe_vpc_classic_link_dns_support)
    - [describe_vpc_endpoint_connection_notifications](#describe_vpc_endpoint_connection_notifications)
    - [describe_vpc_endpoint_connections](#describe_vpc_endpoint_connections)
    - [describe_vpc_endpoint_service_configurations](#describe_vpc_endpoint_service_configurations)
    - [describe_vpc_endpoint_service_permissions](#describe_vpc_endpoint_service_permissions)
    - [describe_vpc_endpoint_services](#describe_vpc_endpoint_services)
    - [describe_vpc_endpoints](#describe_vpc_endpoints)
    - [describe_vpc_peering_connections](#describe_vpc_peering_connections)
    - [describe_vpcs](#describe_vpcs)
    - [describe_vpn_connections](#describe_vpn_connections)
    - [describe_vpn_gateways](#describe_vpn_gateways)
    - [detach_classic_link_vpc](#detach_classic_link_vpc)
    - [detach_internet_gateway](#detach_internet_gateway)
    - [detach_network_interface](#detach_network_interface)
    - [detach_volume](#detach_volume)
    - [detach_vpn_gateway](#detach_vpn_gateway)
    - [disable_ebs_encryption_by_default](#disable_ebs_encryption_by_default)
    - [disable_fast_snapshot_restores](#disable_fast_snapshot_restores)
    - [disable_image_deprecation](#disable_image_deprecation)
    - [disable_ipam_organization_admin_account](#disable_ipam_organization_admin_account)
    - [disable_serial_console_access](#disable_serial_console_access)
    - [disable_transit_gateway_route_table_propagation](#disable_transit_gateway_route_table_propagation)
    - [disable_vgw_route_propagation](#disable_vgw_route_propagation)
    - [disable_vpc_classic_link](#disable_vpc_classic_link)
    - [disable_vpc_classic_link_dns_support](#disable_vpc_classic_link_dns_support)
    - [disassociate_address](#disassociate_address)
    - [disassociate_client_vpn_target_network](#disassociate_client_vpn_target_network)
    - [disassociate_enclave_certificate_iam_role](#disassociate_enclave_certificate_iam_role)
    - [disassociate_iam_instance_profile](#disassociate_iam_instance_profile)
    - [disassociate_instance_event_window](#disassociate_instance_event_window)
    - [disassociate_route_table](#disassociate_route_table)
    - [disassociate_subnet_cidr_block](#disassociate_subnet_cidr_block)
    - [disassociate_transit_gateway_multicast_domain](#disassociate_transit_gateway_multicast_domain)
    - [disassociate_transit_gateway_route_table](#disassociate_transit_gateway_route_table)
    - [disassociate_trunk_interface](#disassociate_trunk_interface)
    - [disassociate_vpc_cidr_block](#disassociate_vpc_cidr_block)
    - [enable_ebs_encryption_by_default](#enable_ebs_encryption_by_default)
    - [enable_fast_snapshot_restores](#enable_fast_snapshot_restores)
    - [enable_image_deprecation](#enable_image_deprecation)
    - [enable_ipam_organization_admin_account](#enable_ipam_organization_admin_account)
    - [enable_serial_console_access](#enable_serial_console_access)
    - [enable_transit_gateway_route_table_propagation](#enable_transit_gateway_route_table_propagation)
    - [enable_vgw_route_propagation](#enable_vgw_route_propagation)
    - [enable_volume_io](#enable_volume_io)
    - [enable_vpc_classic_link](#enable_vpc_classic_link)
    - [enable_vpc_classic_link_dns_support](#enable_vpc_classic_link_dns_support)
    - [export_client_vpn_client_certificate_revocation_list](#export_client_vpn_client_certificate_revocation_list)
    - [export_client_vpn_client_configuration](#export_client_vpn_client_configuration)
    - [export_image](#export_image)
    - [export_transit_gateway_routes](#export_transit_gateway_routes)
    - [generate_presigned_url](#generate_presigned_url)
    - [get_associated_enclave_certificate_iam_roles](#get_associated_enclave_certificate_iam_roles)
    - [get_associated_ipv6_pool_cidrs](#get_associated_ipv6_pool_cidrs)
    - [get_capacity_reservation_usage](#get_capacity_reservation_usage)
    - [get_coip_pool_usage](#get_coip_pool_usage)
    - [get_console_output](#get_console_output)
    - [get_console_screenshot](#get_console_screenshot)
    - [get_default_credit_specification](#get_default_credit_specification)
    - [get_ebs_default_kms_key_id](#get_ebs_default_kms_key_id)
    - [get_ebs_encryption_by_default](#get_ebs_encryption_by_default)
    - [get_flow_logs_integration_template](#get_flow_logs_integration_template)
    - [get_groups_for_capacity_reservation](#get_groups_for_capacity_reservation)
    - [get_host_reservation_purchase_preview](#get_host_reservation_purchase_preview)
    - [get_instance_types_from_instance_requirements](#get_instance_types_from_instance_requirements)
    - [get_ipam_address_history](#get_ipam_address_history)
    - [get_ipam_pool_allocations](#get_ipam_pool_allocations)
    - [get_ipam_pool_cidrs](#get_ipam_pool_cidrs)
    - [get_ipam_resource_cidrs](#get_ipam_resource_cidrs)
    - [get_launch_template_data](#get_launch_template_data)
    - [get_managed_prefix_list_associations](#get_managed_prefix_list_associations)
    - [get_managed_prefix_list_entries](#get_managed_prefix_list_entries)
    - [get_network_insights_access_scope_analysis_findings](#get_network_insights_access_scope_analysis_findings)
    - [get_network_insights_access_scope_content](#get_network_insights_access_scope_content)
    - [get_password_data](#get_password_data)
    - [get_reserved_instances_exchange_quote](#get_reserved_instances_exchange_quote)
    - [get_serial_console_access_status](#get_serial_console_access_status)
    - [get_spot_placement_scores](#get_spot_placement_scores)
    - [get_subnet_cidr_reservations](#get_subnet_cidr_reservations)
    - [get_transit_gateway_attachment_propagations](#get_transit_gateway_attachment_propagations)
    - [get_transit_gateway_multicast_domain_associations](#get_transit_gateway_multicast_domain_associations)
    - [get_transit_gateway_prefix_list_references](#get_transit_gateway_prefix_list_references)
    - [get_transit_gateway_route_table_associations](#get_transit_gateway_route_table_associations)
    - [get_transit_gateway_route_table_propagations](#get_transit_gateway_route_table_propagations)
    - [get_vpn_connection_device_sample_configuration](#get_vpn_connection_device_sample_configuration)
    - [get_vpn_connection_device_types](#get_vpn_connection_device_types)
    - [import_client_vpn_client_certificate_revocation_list](#import_client_vpn_client_certificate_revocation_list)
    - [import_image](#import_image)
    - [import_instance](#import_instance)
    - [import_key_pair](#import_key_pair)
    - [import_snapshot](#import_snapshot)
    - [import_volume](#import_volume)
    - [list_snapshots_in_recycle_bin](#list_snapshots_in_recycle_bin)
    - [modify_address_attribute](#modify_address_attribute)
    - [modify_availability_zone_group](#modify_availability_zone_group)
    - [modify_capacity_reservation](#modify_capacity_reservation)
    - [modify_capacity_reservation_fleet](#modify_capacity_reservation_fleet)
    - [modify_client_vpn_endpoint](#modify_client_vpn_endpoint)
    - [modify_default_credit_specification](#modify_default_credit_specification)
    - [modify_ebs_default_kms_key_id](#modify_ebs_default_kms_key_id)
    - [modify_fleet](#modify_fleet)
    - [modify_fpga_image_attribute](#modify_fpga_image_attribute)
    - [modify_hosts](#modify_hosts)
    - [modify_id_format](#modify_id_format)
    - [modify_identity_id_format](#modify_identity_id_format)
    - [modify_image_attribute](#modify_image_attribute)
    - [modify_instance_attribute](#modify_instance_attribute)
    - [modify_instance_capacity_reservation_attributes](#modify_instance_capacity_reservation_attributes)
    - [modify_instance_credit_specification](#modify_instance_credit_specification)
    - [modify_instance_event_start_time](#modify_instance_event_start_time)
    - [modify_instance_event_window](#modify_instance_event_window)
    - [modify_instance_metadata_options](#modify_instance_metadata_options)
    - [modify_instance_placement](#modify_instance_placement)
    - [modify_ipam](#modify_ipam)
    - [modify_ipam_pool](#modify_ipam_pool)
    - [modify_ipam_resource_cidr](#modify_ipam_resource_cidr)
    - [modify_ipam_scope](#modify_ipam_scope)
    - [modify_launch_template](#modify_launch_template)
    - [modify_managed_prefix_list](#modify_managed_prefix_list)
    - [modify_network_interface_attribute](#modify_network_interface_attribute)
    - [modify_private_dns_name_options](#modify_private_dns_name_options)
    - [modify_reserved_instances](#modify_reserved_instances)
    - [modify_security_group_rules](#modify_security_group_rules)
    - [modify_snapshot_attribute](#modify_snapshot_attribute)
    - [modify_snapshot_tier](#modify_snapshot_tier)
    - [modify_spot_fleet_request](#modify_spot_fleet_request)
    - [modify_subnet_attribute](#modify_subnet_attribute)
    - [modify_traffic_mirror_filter_network_services](#modify_traffic_mirror_filter_network_services)
    - [modify_traffic_mirror_filter_rule](#modify_traffic_mirror_filter_rule)
    - [modify_traffic_mirror_session](#modify_traffic_mirror_session)
    - [modify_transit_gateway](#modify_transit_gateway)
    - [modify_transit_gateway_prefix_list_reference](#modify_transit_gateway_prefix_list_reference)
    - [modify_transit_gateway_vpc_attachment](#modify_transit_gateway_vpc_attachment)
    - [modify_volume](#modify_volume)
    - [modify_volume_attribute](#modify_volume_attribute)
    - [modify_vpc_attribute](#modify_vpc_attribute)
    - [modify_vpc_endpoint](#modify_vpc_endpoint)
    - [modify_vpc_endpoint_connection_notification](#modify_vpc_endpoint_connection_notification)
    - [modify_vpc_endpoint_service_configuration](#modify_vpc_endpoint_service_configuration)
    - [modify_vpc_endpoint_service_permissions](#modify_vpc_endpoint_service_permissions)
    - [modify_vpc_peering_connection_options](#modify_vpc_peering_connection_options)
    - [modify_vpc_tenancy](#modify_vpc_tenancy)
    - [modify_vpn_connection](#modify_vpn_connection)
    - [modify_vpn_connection_options](#modify_vpn_connection_options)
    - [modify_vpn_tunnel_certificate](#modify_vpn_tunnel_certificate)
    - [modify_vpn_tunnel_options](#modify_vpn_tunnel_options)
    - [monitor_instances](#monitor_instances)
    - [move_address_to_vpc](#move_address_to_vpc)
    - [move_byoip_cidr_to_ipam](#move_byoip_cidr_to_ipam)
    - [provision_byoip_cidr](#provision_byoip_cidr)
    - [provision_ipam_pool_cidr](#provision_ipam_pool_cidr)
    - [provision_public_ipv4_pool_cidr](#provision_public_ipv4_pool_cidr)
    - [purchase_host_reservation](#purchase_host_reservation)
    - [purchase_reserved_instances_offering](#purchase_reserved_instances_offering)
    - [purchase_scheduled_instances](#purchase_scheduled_instances)
    - [reboot_instances](#reboot_instances)
    - [register_image](#register_image)
    - [register_instance_event_notification_attributes](#register_instance_event_notification_attributes)
    - [register_transit_gateway_multicast_group_members](#register_transit_gateway_multicast_group_members)
    - [register_transit_gateway_multicast_group_sources](#register_transit_gateway_multicast_group_sources)
    - [reject_transit_gateway_multicast_domain_associations](#reject_transit_gateway_multicast_domain_associations)
    - [reject_transit_gateway_peering_attachment](#reject_transit_gateway_peering_attachment)
    - [reject_transit_gateway_vpc_attachment](#reject_transit_gateway_vpc_attachment)
    - [reject_vpc_endpoint_connections](#reject_vpc_endpoint_connections)
    - [reject_vpc_peering_connection](#reject_vpc_peering_connection)
    - [release_address](#release_address)
    - [release_hosts](#release_hosts)
    - [release_ipam_pool_allocation](#release_ipam_pool_allocation)
    - [replace_iam_instance_profile_association](#replace_iam_instance_profile_association)
    - [replace_network_acl_association](#replace_network_acl_association)
    - [replace_network_acl_entry](#replace_network_acl_entry)
    - [replace_route](#replace_route)
    - [replace_route_table_association](#replace_route_table_association)
    - [replace_transit_gateway_route](#replace_transit_gateway_route)
    - [report_instance_status](#report_instance_status)
    - [request_spot_fleet](#request_spot_fleet)
    - [request_spot_instances](#request_spot_instances)
    - [reset_address_attribute](#reset_address_attribute)
    - [reset_ebs_default_kms_key_id](#reset_ebs_default_kms_key_id)
    - [reset_fpga_image_attribute](#reset_fpga_image_attribute)
    - [reset_image_attribute](#reset_image_attribute)
    - [reset_instance_attribute](#reset_instance_attribute)
    - [reset_network_interface_attribute](#reset_network_interface_attribute)
    - [reset_snapshot_attribute](#reset_snapshot_attribute)
    - [restore_address_to_classic](#restore_address_to_classic)
    - [restore_managed_prefix_list_version](#restore_managed_prefix_list_version)
    - [restore_snapshot_from_recycle_bin](#restore_snapshot_from_recycle_bin)
    - [restore_snapshot_tier](#restore_snapshot_tier)
    - [revoke_client_vpn_ingress](#revoke_client_vpn_ingress)
    - [revoke_security_group_egress](#revoke_security_group_egress)
    - [revoke_security_group_ingress](#revoke_security_group_ingress)
    - [run_instances](#run_instances)
    - [run_scheduled_instances](#run_scheduled_instances)
    - [search_local_gateway_routes](#search_local_gateway_routes)
    - [search_transit_gateway_multicast_groups](#search_transit_gateway_multicast_groups)
    - [search_transit_gateway_routes](#search_transit_gateway_routes)
    - [send_diagnostic_interrupt](#send_diagnostic_interrupt)
    - [start_instances](#start_instances)
    - [start_network_insights_access_scope_analysis](#start_network_insights_access_scope_analysis)
    - [start_network_insights_analysis](#start_network_insights_analysis)
    - [start_vpc_endpoint_service_private_dns_verification](#start_vpc_endpoint_service_private_dns_verification)
    - [stop_instances](#stop_instances)
    - [terminate_client_vpn_connections](#terminate_client_vpn_connections)
    - [terminate_instances](#terminate_instances)
    - [unassign_ipv6_addresses](#unassign_ipv6_addresses)
    - [unassign_private_ip_addresses](#unassign_private_ip_addresses)
    - [unmonitor_instances](#unmonitor_instances)
    - [update_security_group_rule_descriptions_egress](#update_security_group_rule_descriptions_egress)
    - [update_security_group_rule_descriptions_ingress](#update_security_group_rule_descriptions_ingress)
    - [withdraw_byoip_cidr](#withdraw_byoip_cidr)
    - [get_paginator](#get_paginator)
    - [get_waiter](#get_waiter)

<a id="ec2client"></a>

## EC2Client

Type annotations for `aiobotocore.create_client("ec2")`

Can be used directly:

```python
from aiobotocore.session import Session
from types_aiobotocore_ec2.client import EC2Client

def get_ec2_client() -> EC2Client:
    return Session().client("ec2")
```

Boto3 documentation:
[EC2.Client](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client)

<a id="exceptions"></a>

## Exceptions

`boto3` client exceptions are generated in runtime. This class can be used for
static analysis directly:

```python
from types_aiobotocore_ec2.client import Exceptions

def handle_error(exc: Exceptions.ClientError) -> None:
    ...
```

Exceptions:

- `Exceptions.ClientError`

<a id="methods"></a>

## Methods

<a id="exceptions"></a>

### exceptions

EC2Client exceptions.

Type annotations for `aiobotocore.create_client("ec2").exceptions` method.

Boto3 documentation:
[EC2.Client.exceptions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.exceptions)

Returns [Exceptions](#exceptions).

<a id="accept_reserved_instances_exchange_quote"></a>

### accept_reserved_instances_exchange_quote

Accepts the Convertible Reserved Instance exchange quote described in the
GetReservedInstancesExchangeQuote call.

Type annotations for
`aiobotocore.create_client("ec2").accept_reserved_instances_exchange_quote`
method.

Boto3 documentation:
[EC2.Client.accept_reserved_instances_exchange_quote](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.accept_reserved_instances_exchange_quote)

Asynchronous method. Use `await accept_reserved_instances_exchange_quote(...)`
for a synchronous call.

Arguments mapping described in
[AcceptReservedInstancesExchangeQuoteRequestRequestTypeDef](./type_defs.md#acceptreservedinstancesexchangequoterequestrequesttypedef).

Keyword-only arguments:

- `ReservedInstanceIds`: `Sequence`\[`str`\] *(required)*
- `DryRun`: `bool`
- `TargetConfigurations`:
  `Sequence`\[[TargetConfigurationRequestTypeDef](./type_defs.md#targetconfigurationrequesttypedef)\]

Returns a `Coroutine` for
[AcceptReservedInstancesExchangeQuoteResultTypeDef](./type_defs.md#acceptreservedinstancesexchangequoteresulttypedef).

<a id="accept_transit_gateway_multicast_domain_associations"></a>

### accept_transit_gateway_multicast_domain_associations

Accepts a request to associate subnets with a transit gateway multicast domain.

Type annotations for
`aiobotocore.create_client("ec2").accept_transit_gateway_multicast_domain_associations`
method.

Boto3 documentation:
[EC2.Client.accept_transit_gateway_multicast_domain_associations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.accept_transit_gateway_multicast_domain_associations)

Asynchronous method. Use
`await accept_transit_gateway_multicast_domain_associations(...)` for a
synchronous call.

Arguments mapping described in
[AcceptTransitGatewayMulticastDomainAssociationsRequestRequestTypeDef](./type_defs.md#accepttransitgatewaymulticastdomainassociationsrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayMulticastDomainId`: `str`
- `TransitGatewayAttachmentId`: `str`
- `SubnetIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[AcceptTransitGatewayMulticastDomainAssociationsResultTypeDef](./type_defs.md#accepttransitgatewaymulticastdomainassociationsresulttypedef).

<a id="accept_transit_gateway_peering_attachment"></a>

### accept_transit_gateway_peering_attachment

Accepts a transit gateway peering attachment request.

Type annotations for
`aiobotocore.create_client("ec2").accept_transit_gateway_peering_attachment`
method.

Boto3 documentation:
[EC2.Client.accept_transit_gateway_peering_attachment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.accept_transit_gateway_peering_attachment)

Asynchronous method. Use `await accept_transit_gateway_peering_attachment(...)`
for a synchronous call.

Arguments mapping described in
[AcceptTransitGatewayPeeringAttachmentRequestRequestTypeDef](./type_defs.md#accepttransitgatewaypeeringattachmentrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayAttachmentId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[AcceptTransitGatewayPeeringAttachmentResultTypeDef](./type_defs.md#accepttransitgatewaypeeringattachmentresulttypedef).

<a id="accept_transit_gateway_vpc_attachment"></a>

### accept_transit_gateway_vpc_attachment

Accepts a request to attach a VPC to a transit gateway.

Type annotations for
`aiobotocore.create_client("ec2").accept_transit_gateway_vpc_attachment`
method.

Boto3 documentation:
[EC2.Client.accept_transit_gateway_vpc_attachment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.accept_transit_gateway_vpc_attachment)

Asynchronous method. Use `await accept_transit_gateway_vpc_attachment(...)` for
a synchronous call.

Arguments mapping described in
[AcceptTransitGatewayVpcAttachmentRequestRequestTypeDef](./type_defs.md#accepttransitgatewayvpcattachmentrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayAttachmentId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[AcceptTransitGatewayVpcAttachmentResultTypeDef](./type_defs.md#accepttransitgatewayvpcattachmentresulttypedef).

<a id="accept_vpc_endpoint_connections"></a>

### accept_vpc_endpoint_connections

Accepts one or more interface VPC endpoint connection requests to your VPC
endpoint service.

Type annotations for
`aiobotocore.create_client("ec2").accept_vpc_endpoint_connections` method.

Boto3 documentation:
[EC2.Client.accept_vpc_endpoint_connections](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.accept_vpc_endpoint_connections)

Asynchronous method. Use `await accept_vpc_endpoint_connections(...)` for a
synchronous call.

Arguments mapping described in
[AcceptVpcEndpointConnectionsRequestRequestTypeDef](./type_defs.md#acceptvpcendpointconnectionsrequestrequesttypedef).

Keyword-only arguments:

- `ServiceId`: `str` *(required)*
- `VpcEndpointIds`: `Sequence`\[`str`\] *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[AcceptVpcEndpointConnectionsResultTypeDef](./type_defs.md#acceptvpcendpointconnectionsresulttypedef).

<a id="accept_vpc_peering_connection"></a>

### accept_vpc_peering_connection

Accept a VPC peering connection request.

Type annotations for
`aiobotocore.create_client("ec2").accept_vpc_peering_connection` method.

Boto3 documentation:
[EC2.Client.accept_vpc_peering_connection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.accept_vpc_peering_connection)

Asynchronous method. Use `await accept_vpc_peering_connection(...)` for a
synchronous call.

Arguments mapping described in
[AcceptVpcPeeringConnectionRequestRequestTypeDef](./type_defs.md#acceptvpcpeeringconnectionrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `VpcPeeringConnectionId`: `str`

Returns a `Coroutine` for
[AcceptVpcPeeringConnectionResultTypeDef](./type_defs.md#acceptvpcpeeringconnectionresulttypedef).

<a id="advertise_byoip_cidr"></a>

### advertise_byoip_cidr

Advertises an IPv4 or IPv6 address range that is provisioned for use with your
Amazon Web Services resources through bring your own IP addresses (BYOIP).

Type annotations for `aiobotocore.create_client("ec2").advertise_byoip_cidr`
method.

Boto3 documentation:
[EC2.Client.advertise_byoip_cidr](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.advertise_byoip_cidr)

Asynchronous method. Use `await advertise_byoip_cidr(...)` for a synchronous
call.

Arguments mapping described in
[AdvertiseByoipCidrRequestRequestTypeDef](./type_defs.md#advertisebyoipcidrrequestrequesttypedef).

Keyword-only arguments:

- `Cidr`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[AdvertiseByoipCidrResultTypeDef](./type_defs.md#advertisebyoipcidrresulttypedef).

<a id="allocate_address"></a>

### allocate_address

Allocates an Elastic IP address to your Amazon Web Services account.

Type annotations for `aiobotocore.create_client("ec2").allocate_address`
method.

Boto3 documentation:
[EC2.Client.allocate_address](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.allocate_address)

Asynchronous method. Use `await allocate_address(...)` for a synchronous call.

Arguments mapping described in
[AllocateAddressRequestRequestTypeDef](./type_defs.md#allocateaddressrequestrequesttypedef).

Keyword-only arguments:

- `Domain`: [DomainTypeType](./literals.md#domaintypetype)
- `Address`: `str`
- `PublicIpv4Pool`: `str`
- `NetworkBorderGroup`: `str`
- `CustomerOwnedIpv4Pool`: `str`
- `DryRun`: `bool`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for
[AllocateAddressResultTypeDef](./type_defs.md#allocateaddressresulttypedef).

<a id="allocate_hosts"></a>

### allocate_hosts

Allocates a Dedicated Host to your account.

Type annotations for `aiobotocore.create_client("ec2").allocate_hosts` method.

Boto3 documentation:
[EC2.Client.allocate_hosts](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.allocate_hosts)

Asynchronous method. Use `await allocate_hosts(...)` for a synchronous call.

Arguments mapping described in
[AllocateHostsRequestRequestTypeDef](./type_defs.md#allocatehostsrequestrequesttypedef).

Keyword-only arguments:

- `AvailabilityZone`: `str` *(required)*
- `Quantity`: `int` *(required)*
- `AutoPlacement`: [AutoPlacementType](./literals.md#autoplacementtype)
- `ClientToken`: `str`
- `InstanceType`: `str`
- `InstanceFamily`: `str`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `HostRecovery`: [HostRecoveryType](./literals.md#hostrecoverytype)

Returns a `Coroutine` for
[AllocateHostsResultTypeDef](./type_defs.md#allocatehostsresulttypedef).

<a id="allocate_ipam_pool_cidr"></a>

### allocate_ipam_pool_cidr

Allocate a CIDR from an IPAM pool.

Type annotations for `aiobotocore.create_client("ec2").allocate_ipam_pool_cidr`
method.

Boto3 documentation:
[EC2.Client.allocate_ipam_pool_cidr](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.allocate_ipam_pool_cidr)

Asynchronous method. Use `await allocate_ipam_pool_cidr(...)` for a synchronous
call.

Arguments mapping described in
[AllocateIpamPoolCidrRequestRequestTypeDef](./type_defs.md#allocateipampoolcidrrequestrequesttypedef).

Keyword-only arguments:

- `IpamPoolId`: `str` *(required)*
- `DryRun`: `bool`
- `Cidr`: `str`
- `NetmaskLength`: `int`
- `ClientToken`: `str`
- `Description`: `str`
- `PreviewNextCidr`: `bool`
- `DisallowedCidrs`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[AllocateIpamPoolCidrResultTypeDef](./type_defs.md#allocateipampoolcidrresulttypedef).

<a id="apply_security_groups_to_client_vpn_target_network"></a>

### apply_security_groups_to_client_vpn_target_network

Applies a security group to the association between the target network and the
Client VPN endpoint.

Type annotations for
`aiobotocore.create_client("ec2").apply_security_groups_to_client_vpn_target_network`
method.

Boto3 documentation:
[EC2.Client.apply_security_groups_to_client_vpn_target_network](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.apply_security_groups_to_client_vpn_target_network)

Asynchronous method. Use
`await apply_security_groups_to_client_vpn_target_network(...)` for a
synchronous call.

Arguments mapping described in
[ApplySecurityGroupsToClientVpnTargetNetworkRequestRequestTypeDef](./type_defs.md#applysecuritygroupstoclientvpntargetnetworkrequestrequesttypedef).

Keyword-only arguments:

- `ClientVpnEndpointId`: `str` *(required)*
- `VpcId`: `str` *(required)*
- `SecurityGroupIds`: `Sequence`\[`str`\] *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[ApplySecurityGroupsToClientVpnTargetNetworkResultTypeDef](./type_defs.md#applysecuritygroupstoclientvpntargetnetworkresulttypedef).

<a id="assign_ipv6_addresses"></a>

### assign_ipv6_addresses

Assigns one or more IPv6 addresses to the specified network interface.

Type annotations for `aiobotocore.create_client("ec2").assign_ipv6_addresses`
method.

Boto3 documentation:
[EC2.Client.assign_ipv6_addresses](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.assign_ipv6_addresses)

Asynchronous method. Use `await assign_ipv6_addresses(...)` for a synchronous
call.

Arguments mapping described in
[AssignIpv6AddressesRequestRequestTypeDef](./type_defs.md#assignipv6addressesrequestrequesttypedef).

Keyword-only arguments:

- `NetworkInterfaceId`: `str` *(required)*
- `Ipv6AddressCount`: `int`
- `Ipv6Addresses`: `Sequence`\[`str`\]
- `Ipv6PrefixCount`: `int`
- `Ipv6Prefixes`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[AssignIpv6AddressesResultTypeDef](./type_defs.md#assignipv6addressesresulttypedef).

<a id="assign_private_ip_addresses"></a>

### assign_private_ip_addresses

Assigns one or more secondary private IP addresses to the specified network
interface.

Type annotations for
`aiobotocore.create_client("ec2").assign_private_ip_addresses` method.

Boto3 documentation:
[EC2.Client.assign_private_ip_addresses](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.assign_private_ip_addresses)

Asynchronous method. Use `await assign_private_ip_addresses(...)` for a
synchronous call.

Arguments mapping described in
[AssignPrivateIpAddressesRequestRequestTypeDef](./type_defs.md#assignprivateipaddressesrequestrequesttypedef).

Keyword-only arguments:

- `NetworkInterfaceId`: `str` *(required)*
- `AllowReassignment`: `bool`
- `PrivateIpAddresses`: `Sequence`\[`str`\]
- `SecondaryPrivateIpAddressCount`: `int`
- `Ipv4Prefixes`: `Sequence`\[`str`\]
- `Ipv4PrefixCount`: `int`

Returns a `Coroutine` for
[AssignPrivateIpAddressesResultTypeDef](./type_defs.md#assignprivateipaddressesresulttypedef).

<a id="associate_address"></a>

### associate_address

Associates an Elastic IP address, or carrier IP address (for instances that are
in subnets in Wavelength Zones) with an instance or a network interface.

Type annotations for `aiobotocore.create_client("ec2").associate_address`
method.

Boto3 documentation:
[EC2.Client.associate_address](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.associate_address)

Asynchronous method. Use `await associate_address(...)` for a synchronous call.

Arguments mapping described in
[AssociateAddressRequestRequestTypeDef](./type_defs.md#associateaddressrequestrequesttypedef).

Keyword-only arguments:

- `AllocationId`: `str`
- `InstanceId`: `str`
- `PublicIp`: `str`
- `AllowReassociation`: `bool`
- `DryRun`: `bool`
- `NetworkInterfaceId`: `str`
- `PrivateIpAddress`: `str`

Returns a `Coroutine` for
[AssociateAddressResultTypeDef](./type_defs.md#associateaddressresulttypedef).

<a id="associate_client_vpn_target_network"></a>

### associate_client_vpn_target_network

Associates a target network with a Client VPN endpoint.

Type annotations for
`aiobotocore.create_client("ec2").associate_client_vpn_target_network` method.

Boto3 documentation:
[EC2.Client.associate_client_vpn_target_network](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.associate_client_vpn_target_network)

Asynchronous method. Use `await associate_client_vpn_target_network(...)` for a
synchronous call.

Arguments mapping described in
[AssociateClientVpnTargetNetworkRequestRequestTypeDef](./type_defs.md#associateclientvpntargetnetworkrequestrequesttypedef).

Keyword-only arguments:

- `ClientVpnEndpointId`: `str` *(required)*
- `SubnetId`: `str` *(required)*
- `ClientToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[AssociateClientVpnTargetNetworkResultTypeDef](./type_defs.md#associateclientvpntargetnetworkresulttypedef).

<a id="associate_dhcp_options"></a>

### associate_dhcp_options

Associates a set of DHCP options (that you've previously created) with the
specified VPC, or associates no DHCP options with the VPC.

Type annotations for `aiobotocore.create_client("ec2").associate_dhcp_options`
method.

Boto3 documentation:
[EC2.Client.associate_dhcp_options](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.associate_dhcp_options)

Asynchronous method. Use `await associate_dhcp_options(...)` for a synchronous
call.

Arguments mapping described in
[AssociateDhcpOptionsRequestRequestTypeDef](./type_defs.md#associatedhcpoptionsrequestrequesttypedef).

Keyword-only arguments:

- `DhcpOptionsId`: `str` *(required)*
- `VpcId`: `str` *(required)*
- `DryRun`: `bool`

<a id="associate_enclave_certificate_iam_role"></a>

### associate_enclave_certificate_iam_role

Associates an Identity and Access Management (IAM) role with an Certificate
Manager (ACM) certificate.

Type annotations for
`aiobotocore.create_client("ec2").associate_enclave_certificate_iam_role`
method.

Boto3 documentation:
[EC2.Client.associate_enclave_certificate_iam_role](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.associate_enclave_certificate_iam_role)

Asynchronous method. Use `await associate_enclave_certificate_iam_role(...)`
for a synchronous call.

Arguments mapping described in
[AssociateEnclaveCertificateIamRoleRequestRequestTypeDef](./type_defs.md#associateenclavecertificateiamrolerequestrequesttypedef).

Keyword-only arguments:

- `CertificateArn`: `str`
- `RoleArn`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[AssociateEnclaveCertificateIamRoleResultTypeDef](./type_defs.md#associateenclavecertificateiamroleresulttypedef).

<a id="associate_iam_instance_profile"></a>

### associate_iam_instance_profile

Associates an IAM instance profile with a running or stopped instance.

Type annotations for
`aiobotocore.create_client("ec2").associate_iam_instance_profile` method.

Boto3 documentation:
[EC2.Client.associate_iam_instance_profile](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.associate_iam_instance_profile)

Asynchronous method. Use `await associate_iam_instance_profile(...)` for a
synchronous call.

Arguments mapping described in
[AssociateIamInstanceProfileRequestRequestTypeDef](./type_defs.md#associateiaminstanceprofilerequestrequesttypedef).

Keyword-only arguments:

- `IamInstanceProfile`:
  [IamInstanceProfileSpecificationTypeDef](./type_defs.md#iaminstanceprofilespecificationtypedef)
  *(required)*
- `InstanceId`: `str` *(required)*

Returns a `Coroutine` for
[AssociateIamInstanceProfileResultTypeDef](./type_defs.md#associateiaminstanceprofileresulttypedef).

<a id="associate_instance_event_window"></a>

### associate_instance_event_window

Associates one or more targets with an event window.

Type annotations for
`aiobotocore.create_client("ec2").associate_instance_event_window` method.

Boto3 documentation:
[EC2.Client.associate_instance_event_window](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.associate_instance_event_window)

Asynchronous method. Use `await associate_instance_event_window(...)` for a
synchronous call.

Arguments mapping described in
[AssociateInstanceEventWindowRequestRequestTypeDef](./type_defs.md#associateinstanceeventwindowrequestrequesttypedef).

Keyword-only arguments:

- `InstanceEventWindowId`: `str` *(required)*
- `AssociationTarget`:
  [InstanceEventWindowAssociationRequestTypeDef](./type_defs.md#instanceeventwindowassociationrequesttypedef)
  *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[AssociateInstanceEventWindowResultTypeDef](./type_defs.md#associateinstanceeventwindowresulttypedef).

<a id="associate_route_table"></a>

### associate_route_table

Associates a subnet in your VPC or an internet gateway or virtual private
gateway attached to your VPC with a route table in your VPC.

Type annotations for `aiobotocore.create_client("ec2").associate_route_table`
method.

Boto3 documentation:
[EC2.Client.associate_route_table](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.associate_route_table)

Asynchronous method. Use `await associate_route_table(...)` for a synchronous
call.

Arguments mapping described in
[AssociateRouteTableRequestRequestTypeDef](./type_defs.md#associateroutetablerequestrequesttypedef).

Keyword-only arguments:

- `RouteTableId`: `str` *(required)*
- `DryRun`: `bool`
- `SubnetId`: `str`
- `GatewayId`: `str`

Returns a `Coroutine` for
[AssociateRouteTableResultTypeDef](./type_defs.md#associateroutetableresulttypedef).

<a id="associate_subnet_cidr_block"></a>

### associate_subnet_cidr_block

Associates a CIDR block with your subnet.

Type annotations for
`aiobotocore.create_client("ec2").associate_subnet_cidr_block` method.

Boto3 documentation:
[EC2.Client.associate_subnet_cidr_block](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.associate_subnet_cidr_block)

Asynchronous method. Use `await associate_subnet_cidr_block(...)` for a
synchronous call.

Arguments mapping described in
[AssociateSubnetCidrBlockRequestRequestTypeDef](./type_defs.md#associatesubnetcidrblockrequestrequesttypedef).

Keyword-only arguments:

- `Ipv6CidrBlock`: `str` *(required)*
- `SubnetId`: `str` *(required)*

Returns a `Coroutine` for
[AssociateSubnetCidrBlockResultTypeDef](./type_defs.md#associatesubnetcidrblockresulttypedef).

<a id="associate_transit_gateway_multicast_domain"></a>

### associate_transit_gateway_multicast_domain

Associates the specified subnets and transit gateway attachments with the
specified transit gateway multicast domain.

Type annotations for
`aiobotocore.create_client("ec2").associate_transit_gateway_multicast_domain`
method.

Boto3 documentation:
[EC2.Client.associate_transit_gateway_multicast_domain](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.associate_transit_gateway_multicast_domain)

Asynchronous method. Use
`await associate_transit_gateway_multicast_domain(...)` for a synchronous call.

Arguments mapping described in
[AssociateTransitGatewayMulticastDomainRequestRequestTypeDef](./type_defs.md#associatetransitgatewaymulticastdomainrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayMulticastDomainId`: `str`
- `TransitGatewayAttachmentId`: `str`
- `SubnetIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[AssociateTransitGatewayMulticastDomainResultTypeDef](./type_defs.md#associatetransitgatewaymulticastdomainresulttypedef).

<a id="associate_transit_gateway_route_table"></a>

### associate_transit_gateway_route_table

Associates the specified attachment with the specified transit gateway route
table.

Type annotations for
`aiobotocore.create_client("ec2").associate_transit_gateway_route_table`
method.

Boto3 documentation:
[EC2.Client.associate_transit_gateway_route_table](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.associate_transit_gateway_route_table)

Asynchronous method. Use `await associate_transit_gateway_route_table(...)` for
a synchronous call.

Arguments mapping described in
[AssociateTransitGatewayRouteTableRequestRequestTypeDef](./type_defs.md#associatetransitgatewayroutetablerequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayRouteTableId`: `str` *(required)*
- `TransitGatewayAttachmentId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[AssociateTransitGatewayRouteTableResultTypeDef](./type_defs.md#associatetransitgatewayroutetableresulttypedef).

<a id="associate_trunk_interface"></a>

### associate_trunk_interface

.

Type annotations for
`aiobotocore.create_client("ec2").associate_trunk_interface` method.

Boto3 documentation:
[EC2.Client.associate_trunk_interface](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.associate_trunk_interface)

Asynchronous method. Use `await associate_trunk_interface(...)` for a
synchronous call.

Arguments mapping described in
[AssociateTrunkInterfaceRequestRequestTypeDef](./type_defs.md#associatetrunkinterfacerequestrequesttypedef).

Keyword-only arguments:

- `BranchInterfaceId`: `str` *(required)*
- `TrunkInterfaceId`: `str` *(required)*
- `VlanId`: `int`
- `GreKey`: `int`
- `ClientToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[AssociateTrunkInterfaceResultTypeDef](./type_defs.md#associatetrunkinterfaceresulttypedef).

<a id="associate_vpc_cidr_block"></a>

### associate_vpc_cidr_block

Associates a CIDR block with your VPC.

Type annotations for
`aiobotocore.create_client("ec2").associate_vpc_cidr_block` method.

Boto3 documentation:
[EC2.Client.associate_vpc_cidr_block](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.associate_vpc_cidr_block)

Asynchronous method. Use `await associate_vpc_cidr_block(...)` for a
synchronous call.

Arguments mapping described in
[AssociateVpcCidrBlockRequestRequestTypeDef](./type_defs.md#associatevpccidrblockrequestrequesttypedef).

Keyword-only arguments:

- `VpcId`: `str` *(required)*
- `AmazonProvidedIpv6CidrBlock`: `bool`
- `CidrBlock`: `str`
- `Ipv6CidrBlockNetworkBorderGroup`: `str`
- `Ipv6Pool`: `str`
- `Ipv6CidrBlock`: `str`
- `Ipv4IpamPoolId`: `str`
- `Ipv4NetmaskLength`: `int`
- `Ipv6IpamPoolId`: `str`
- `Ipv6NetmaskLength`: `int`

Returns a `Coroutine` for
[AssociateVpcCidrBlockResultTypeDef](./type_defs.md#associatevpccidrblockresulttypedef).

<a id="attach_classic_link_vpc"></a>

### attach_classic_link_vpc

Links an EC2-Classic instance to a ClassicLink-enabled VPC through one or more
of the VPC's security groups.

Type annotations for `aiobotocore.create_client("ec2").attach_classic_link_vpc`
method.

Boto3 documentation:
[EC2.Client.attach_classic_link_vpc](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.attach_classic_link_vpc)

Asynchronous method. Use `await attach_classic_link_vpc(...)` for a synchronous
call.

Arguments mapping described in
[AttachClassicLinkVpcRequestRequestTypeDef](./type_defs.md#attachclassiclinkvpcrequestrequesttypedef).

Keyword-only arguments:

- `Groups`: `Sequence`\[`str`\] *(required)*
- `InstanceId`: `str` *(required)*
- `VpcId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[AttachClassicLinkVpcResultTypeDef](./type_defs.md#attachclassiclinkvpcresulttypedef).

<a id="attach_internet_gateway"></a>

### attach_internet_gateway

Attaches an internet gateway or a virtual private gateway to a VPC, enabling
connectivity between the internet and the VPC.

Type annotations for `aiobotocore.create_client("ec2").attach_internet_gateway`
method.

Boto3 documentation:
[EC2.Client.attach_internet_gateway](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.attach_internet_gateway)

Asynchronous method. Use `await attach_internet_gateway(...)` for a synchronous
call.

Arguments mapping described in
[AttachInternetGatewayRequestRequestTypeDef](./type_defs.md#attachinternetgatewayrequestrequesttypedef).

Keyword-only arguments:

- `InternetGatewayId`: `str` *(required)*
- `VpcId`: `str` *(required)*
- `DryRun`: `bool`

<a id="attach_network_interface"></a>

### attach_network_interface

Attaches a network interface to an instance.

Type annotations for
`aiobotocore.create_client("ec2").attach_network_interface` method.

Boto3 documentation:
[EC2.Client.attach_network_interface](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.attach_network_interface)

Asynchronous method. Use `await attach_network_interface(...)` for a
synchronous call.

Arguments mapping described in
[AttachNetworkInterfaceRequestRequestTypeDef](./type_defs.md#attachnetworkinterfacerequestrequesttypedef).

Keyword-only arguments:

- `DeviceIndex`: `int` *(required)*
- `InstanceId`: `str` *(required)*
- `NetworkInterfaceId`: `str` *(required)*
- `DryRun`: `bool`
- `NetworkCardIndex`: `int`

Returns a `Coroutine` for
[AttachNetworkInterfaceResultTypeDef](./type_defs.md#attachnetworkinterfaceresulttypedef).

<a id="attach_volume"></a>

### attach_volume

Attaches an EBS volume to a running or stopped instance and exposes it to the
instance with the specified device name.

Type annotations for `aiobotocore.create_client("ec2").attach_volume` method.

Boto3 documentation:
[EC2.Client.attach_volume](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.attach_volume)

Asynchronous method. Use `await attach_volume(...)` for a synchronous call.

Arguments mapping described in
[AttachVolumeRequestRequestTypeDef](./type_defs.md#attachvolumerequestrequesttypedef).

Keyword-only arguments:

- `Device`: `str` *(required)*
- `InstanceId`: `str` *(required)*
- `VolumeId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[VolumeAttachmentResponseMetadataTypeDef](./type_defs.md#volumeattachmentresponsemetadatatypedef).

<a id="attach_vpn_gateway"></a>

### attach_vpn_gateway

Attaches a virtual private gateway to a VPC.

Type annotations for `aiobotocore.create_client("ec2").attach_vpn_gateway`
method.

Boto3 documentation:
[EC2.Client.attach_vpn_gateway](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.attach_vpn_gateway)

Asynchronous method. Use `await attach_vpn_gateway(...)` for a synchronous
call.

Arguments mapping described in
[AttachVpnGatewayRequestRequestTypeDef](./type_defs.md#attachvpngatewayrequestrequesttypedef).

Keyword-only arguments:

- `VpcId`: `str` *(required)*
- `VpnGatewayId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[AttachVpnGatewayResultTypeDef](./type_defs.md#attachvpngatewayresulttypedef).

<a id="authorize_client_vpn_ingress"></a>

### authorize_client_vpn_ingress

Adds an ingress authorization rule to a Client VPN endpoint.

Type annotations for
`aiobotocore.create_client("ec2").authorize_client_vpn_ingress` method.

Boto3 documentation:
[EC2.Client.authorize_client_vpn_ingress](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.authorize_client_vpn_ingress)

Asynchronous method. Use `await authorize_client_vpn_ingress(...)` for a
synchronous call.

Arguments mapping described in
[AuthorizeClientVpnIngressRequestRequestTypeDef](./type_defs.md#authorizeclientvpningressrequestrequesttypedef).

Keyword-only arguments:

- `ClientVpnEndpointId`: `str` *(required)*
- `TargetNetworkCidr`: `str` *(required)*
- `AccessGroupId`: `str`
- `AuthorizeAllGroups`: `bool`
- `Description`: `str`
- `ClientToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[AuthorizeClientVpnIngressResultTypeDef](./type_defs.md#authorizeclientvpningressresulttypedef).

<a id="authorize_security_group_egress"></a>

### authorize_security_group_egress

Type annotations for
`aiobotocore.create_client("ec2").authorize_security_group_egress` method.

Boto3 documentation:
[EC2.Client.authorize_security_group_egress](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.authorize_security_group_egress)

Asynchronous method. Use `await authorize_security_group_egress(...)` for a
synchronous call.

Arguments mapping described in
[AuthorizeSecurityGroupEgressRequestRequestTypeDef](./type_defs.md#authorizesecuritygroupegressrequestrequesttypedef).

Keyword-only arguments:

- `GroupId`: `str` *(required)*
- `DryRun`: `bool`
- `IpPermissions`:
  `Sequence`\[[IpPermissionTypeDef](./type_defs.md#ippermissiontypedef)\]
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `CidrIp`: `str`
- `FromPort`: `int`
- `IpProtocol`: `str`
- `ToPort`: `int`
- `SourceSecurityGroupName`: `str`
- `SourceSecurityGroupOwnerId`: `str`

Returns a `Coroutine` for
[AuthorizeSecurityGroupEgressResultTypeDef](./type_defs.md#authorizesecuritygroupegressresulttypedef).

<a id="authorize_security_group_ingress"></a>

### authorize_security_group_ingress

Adds the specified inbound (ingress) rules to a security group.

Type annotations for
`aiobotocore.create_client("ec2").authorize_security_group_ingress` method.

Boto3 documentation:
[EC2.Client.authorize_security_group_ingress](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.authorize_security_group_ingress)

Asynchronous method. Use `await authorize_security_group_ingress(...)` for a
synchronous call.

Arguments mapping described in
[AuthorizeSecurityGroupIngressRequestRequestTypeDef](./type_defs.md#authorizesecuritygroupingressrequestrequesttypedef).

Keyword-only arguments:

- `CidrIp`: `str`
- `FromPort`: `int`
- `GroupId`: `str`
- `GroupName`: `str`
- `IpPermissions`:
  `Sequence`\[[IpPermissionTypeDef](./type_defs.md#ippermissiontypedef)\]
- `IpProtocol`: `str`
- `SourceSecurityGroupName`: `str`
- `SourceSecurityGroupOwnerId`: `str`
- `ToPort`: `int`
- `DryRun`: `bool`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for
[AuthorizeSecurityGroupIngressResultTypeDef](./type_defs.md#authorizesecuritygroupingressresulttypedef).

<a id="bundle_instance"></a>

### bundle_instance

Bundles an Amazon instance store-backed Windows instance.

Type annotations for `aiobotocore.create_client("ec2").bundle_instance` method.

Boto3 documentation:
[EC2.Client.bundle_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.bundle_instance)

Asynchronous method. Use `await bundle_instance(...)` for a synchronous call.

Arguments mapping described in
[BundleInstanceRequestRequestTypeDef](./type_defs.md#bundleinstancerequestrequesttypedef).

Keyword-only arguments:

- `InstanceId`: `str` *(required)*
- `Storage`: [StorageTypeDef](./type_defs.md#storagetypedef) *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[BundleInstanceResultTypeDef](./type_defs.md#bundleinstanceresulttypedef).

<a id="can_paginate"></a>

### can_paginate

Check if an operation can be paginated.

Type annotations for `aiobotocore.create_client("ec2").can_paginate` method.

Boto3 documentation:
[EC2.Client.can_paginate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.can_paginate)

Asynchronous method. Use `await can_paginate(...)` for a synchronous call.

Arguments:

- `operation_name`: `str` *(required)*

Returns a `Coroutine` for `bool`.

<a id="cancel_bundle_task"></a>

### cancel_bundle_task

Cancels a bundling operation for an instance store-backed Windows instance.

Type annotations for `aiobotocore.create_client("ec2").cancel_bundle_task`
method.

Boto3 documentation:
[EC2.Client.cancel_bundle_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.cancel_bundle_task)

Asynchronous method. Use `await cancel_bundle_task(...)` for a synchronous
call.

Arguments mapping described in
[CancelBundleTaskRequestRequestTypeDef](./type_defs.md#cancelbundletaskrequestrequesttypedef).

Keyword-only arguments:

- `BundleId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[CancelBundleTaskResultTypeDef](./type_defs.md#cancelbundletaskresulttypedef).

<a id="cancel_capacity_reservation"></a>

### cancel_capacity_reservation

Cancels the specified Capacity Reservation, releases the reserved capacity, and
changes the Capacity Reservation's state to `cancelled` .

Type annotations for
`aiobotocore.create_client("ec2").cancel_capacity_reservation` method.

Boto3 documentation:
[EC2.Client.cancel_capacity_reservation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.cancel_capacity_reservation)

Asynchronous method. Use `await cancel_capacity_reservation(...)` for a
synchronous call.

Arguments mapping described in
[CancelCapacityReservationRequestRequestTypeDef](./type_defs.md#cancelcapacityreservationrequestrequesttypedef).

Keyword-only arguments:

- `CapacityReservationId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[CancelCapacityReservationResultTypeDef](./type_defs.md#cancelcapacityreservationresulttypedef).

<a id="cancel_capacity_reservation_fleets"></a>

### cancel_capacity_reservation_fleets

Cancels one or more Capacity Reservation Fleets.

Type annotations for
`aiobotocore.create_client("ec2").cancel_capacity_reservation_fleets` method.

Boto3 documentation:
[EC2.Client.cancel_capacity_reservation_fleets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.cancel_capacity_reservation_fleets)

Asynchronous method. Use `await cancel_capacity_reservation_fleets(...)` for a
synchronous call.

Arguments mapping described in
[CancelCapacityReservationFleetsRequestRequestTypeDef](./type_defs.md#cancelcapacityreservationfleetsrequestrequesttypedef).

Keyword-only arguments:

- `CapacityReservationFleetIds`: `Sequence`\[`str`\] *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[CancelCapacityReservationFleetsResultTypeDef](./type_defs.md#cancelcapacityreservationfleetsresulttypedef).

<a id="cancel_conversion_task"></a>

### cancel_conversion_task

Cancels an active conversion task.

Type annotations for `aiobotocore.create_client("ec2").cancel_conversion_task`
method.

Boto3 documentation:
[EC2.Client.cancel_conversion_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.cancel_conversion_task)

Asynchronous method. Use `await cancel_conversion_task(...)` for a synchronous
call.

Arguments mapping described in
[CancelConversionRequestRequestTypeDef](./type_defs.md#cancelconversionrequestrequesttypedef).

Keyword-only arguments:

- `ConversionTaskId`: `str` *(required)*
- `DryRun`: `bool`
- `ReasonMessage`: `str`

<a id="cancel_export_task"></a>

### cancel_export_task

Cancels an active export task.

Type annotations for `aiobotocore.create_client("ec2").cancel_export_task`
method.

Boto3 documentation:
[EC2.Client.cancel_export_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.cancel_export_task)

Asynchronous method. Use `await cancel_export_task(...)` for a synchronous
call.

Arguments mapping described in
[CancelExportTaskRequestRequestTypeDef](./type_defs.md#cancelexporttaskrequestrequesttypedef).

Keyword-only arguments:

- `ExportTaskId`: `str` *(required)*

<a id="cancel_import_task"></a>

### cancel_import_task

Cancels an in-process import virtual machine or import snapshot task.

Type annotations for `aiobotocore.create_client("ec2").cancel_import_task`
method.

Boto3 documentation:
[EC2.Client.cancel_import_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.cancel_import_task)

Asynchronous method. Use `await cancel_import_task(...)` for a synchronous
call.

Arguments mapping described in
[CancelImportTaskRequestRequestTypeDef](./type_defs.md#cancelimporttaskrequestrequesttypedef).

Keyword-only arguments:

- `CancelReason`: `str`
- `DryRun`: `bool`
- `ImportTaskId`: `str`

Returns a `Coroutine` for
[CancelImportTaskResultTypeDef](./type_defs.md#cancelimporttaskresulttypedef).

<a id="cancel_reserved_instances_listing"></a>

### cancel_reserved_instances_listing

Cancels the specified Reserved Instance listing in the Reserved Instance
Marketplace.

Type annotations for
`aiobotocore.create_client("ec2").cancel_reserved_instances_listing` method.

Boto3 documentation:
[EC2.Client.cancel_reserved_instances_listing](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.cancel_reserved_instances_listing)

Asynchronous method. Use `await cancel_reserved_instances_listing(...)` for a
synchronous call.

Arguments mapping described in
[CancelReservedInstancesListingRequestRequestTypeDef](./type_defs.md#cancelreservedinstanceslistingrequestrequesttypedef).

Keyword-only arguments:

- `ReservedInstancesListingId`: `str` *(required)*

Returns a `Coroutine` for
[CancelReservedInstancesListingResultTypeDef](./type_defs.md#cancelreservedinstanceslistingresulttypedef).

<a id="cancel_spot_fleet_requests"></a>

### cancel_spot_fleet_requests

Cancels the specified Spot Fleet requests.

Type annotations for
`aiobotocore.create_client("ec2").cancel_spot_fleet_requests` method.

Boto3 documentation:
[EC2.Client.cancel_spot_fleet_requests](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.cancel_spot_fleet_requests)

Asynchronous method. Use `await cancel_spot_fleet_requests(...)` for a
synchronous call.

Arguments mapping described in
[CancelSpotFleetRequestsRequestRequestTypeDef](./type_defs.md#cancelspotfleetrequestsrequestrequesttypedef).

Keyword-only arguments:

- `SpotFleetRequestIds`: `Sequence`\[`str`\] *(required)*
- `TerminateInstances`: `bool` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[CancelSpotFleetRequestsResponseTypeDef](./type_defs.md#cancelspotfleetrequestsresponsetypedef).

<a id="cancel_spot_instance_requests"></a>

### cancel_spot_instance_requests

Cancels one or more Spot Instance requests.

Type annotations for
`aiobotocore.create_client("ec2").cancel_spot_instance_requests` method.

Boto3 documentation:
[EC2.Client.cancel_spot_instance_requests](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.cancel_spot_instance_requests)

Asynchronous method. Use `await cancel_spot_instance_requests(...)` for a
synchronous call.

Arguments mapping described in
[CancelSpotInstanceRequestsRequestRequestTypeDef](./type_defs.md#cancelspotinstancerequestsrequestrequesttypedef).

Keyword-only arguments:

- `SpotInstanceRequestIds`: `Sequence`\[`str`\] *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[CancelSpotInstanceRequestsResultTypeDef](./type_defs.md#cancelspotinstancerequestsresulttypedef).

<a id="confirm_product_instance"></a>

### confirm_product_instance

Determines whether a product code is associated with an instance.

Type annotations for
`aiobotocore.create_client("ec2").confirm_product_instance` method.

Boto3 documentation:
[EC2.Client.confirm_product_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.confirm_product_instance)

Asynchronous method. Use `await confirm_product_instance(...)` for a
synchronous call.

Arguments mapping described in
[ConfirmProductInstanceRequestRequestTypeDef](./type_defs.md#confirmproductinstancerequestrequesttypedef).

Keyword-only arguments:

- `InstanceId`: `str` *(required)*
- `ProductCode`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[ConfirmProductInstanceResultTypeDef](./type_defs.md#confirmproductinstanceresulttypedef).

<a id="copy_fpga_image"></a>

### copy_fpga_image

Copies the specified Amazon FPGA Image (AFI) to the current Region.

Type annotations for `aiobotocore.create_client("ec2").copy_fpga_image` method.

Boto3 documentation:
[EC2.Client.copy_fpga_image](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.copy_fpga_image)

Asynchronous method. Use `await copy_fpga_image(...)` for a synchronous call.

Arguments mapping described in
[CopyFpgaImageRequestRequestTypeDef](./type_defs.md#copyfpgaimagerequestrequesttypedef).

Keyword-only arguments:

- `SourceFpgaImageId`: `str` *(required)*
- `SourceRegion`: `str` *(required)*
- `DryRun`: `bool`
- `Description`: `str`
- `Name`: `str`
- `ClientToken`: `str`

Returns a `Coroutine` for
[CopyFpgaImageResultTypeDef](./type_defs.md#copyfpgaimageresulttypedef).

<a id="copy_image"></a>

### copy_image

Initiates the copy of an AMI.

Type annotations for `aiobotocore.create_client("ec2").copy_image` method.

Boto3 documentation:
[EC2.Client.copy_image](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.copy_image)

Asynchronous method. Use `await copy_image(...)` for a synchronous call.

Arguments mapping described in
[CopyImageRequestRequestTypeDef](./type_defs.md#copyimagerequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `SourceImageId`: `str` *(required)*
- `SourceRegion`: `str` *(required)*
- `ClientToken`: `str`
- `Description`: `str`
- `Encrypted`: `bool`
- `KmsKeyId`: `str`
- `DestinationOutpostArn`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[CopyImageResultTypeDef](./type_defs.md#copyimageresulttypedef).

<a id="copy_snapshot"></a>

### copy_snapshot

Copies a point-in-time snapshot of an EBS volume and stores it in Amazon S3.

Type annotations for `aiobotocore.create_client("ec2").copy_snapshot` method.

Boto3 documentation:
[EC2.Client.copy_snapshot](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.copy_snapshot)

Asynchronous method. Use `await copy_snapshot(...)` for a synchronous call.

Arguments mapping described in
[CopySnapshotRequestRequestTypeDef](./type_defs.md#copysnapshotrequestrequesttypedef).

Keyword-only arguments:

- `SourceRegion`: `str` *(required)*
- `SourceSnapshotId`: `str` *(required)*
- `Description`: `str`
- `DestinationOutpostArn`: `str`
- `DestinationRegion`: `str`
- `Encrypted`: `bool`
- `KmsKeyId`: `str`
- `PresignedUrl`: `str`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[CopySnapshotResultTypeDef](./type_defs.md#copysnapshotresulttypedef).

<a id="create_capacity_reservation"></a>

### create_capacity_reservation

Creates a new Capacity Reservation with the specified attributes.

Type annotations for
`aiobotocore.create_client("ec2").create_capacity_reservation` method.

Boto3 documentation:
[EC2.Client.create_capacity_reservation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_capacity_reservation)

Asynchronous method. Use `await create_capacity_reservation(...)` for a
synchronous call.

Arguments mapping described in
[CreateCapacityReservationRequestRequestTypeDef](./type_defs.md#createcapacityreservationrequestrequesttypedef).

Keyword-only arguments:

- `InstanceType`: `str` *(required)*
- `InstancePlatform`:
  [CapacityReservationInstancePlatformType](./literals.md#capacityreservationinstanceplatformtype)
  *(required)*
- `InstanceCount`: `int` *(required)*
- `ClientToken`: `str`
- `AvailabilityZone`: `str`
- `AvailabilityZoneId`: `str`
- `Tenancy`:
  [CapacityReservationTenancyType](./literals.md#capacityreservationtenancytype)
- `EbsOptimized`: `bool`
- `EphemeralStorage`: `bool`
- `EndDate`: `Union`\[`datetime`, `str`\]
- `EndDateType`: [EndDateTypeType](./literals.md#enddatetypetype)
- `InstanceMatchCriteria`:
  [InstanceMatchCriteriaType](./literals.md#instancematchcriteriatype)
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `DryRun`: `bool`
- `OutpostArn`: `str`

Returns a `Coroutine` for
[CreateCapacityReservationResultTypeDef](./type_defs.md#createcapacityreservationresulttypedef).

<a id="create_capacity_reservation_fleet"></a>

### create_capacity_reservation_fleet

Creates a Capacity Reservation Fleet.

Type annotations for
`aiobotocore.create_client("ec2").create_capacity_reservation_fleet` method.

Boto3 documentation:
[EC2.Client.create_capacity_reservation_fleet](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_capacity_reservation_fleet)

Asynchronous method. Use `await create_capacity_reservation_fleet(...)` for a
synchronous call.

Arguments mapping described in
[CreateCapacityReservationFleetRequestRequestTypeDef](./type_defs.md#createcapacityreservationfleetrequestrequesttypedef).

Keyword-only arguments:

- `InstanceTypeSpecifications`:
  `Sequence`\[[ReservationFleetInstanceSpecificationTypeDef](./type_defs.md#reservationfleetinstancespecificationtypedef)\]
  *(required)*
- `TotalTargetCapacity`: `int` *(required)*
- `AllocationStrategy`: `str`
- `ClientToken`: `str`
- `Tenancy`: `Literal['default']` (see
  [FleetCapacityReservationTenancyType](./literals.md#fleetcapacityreservationtenancytype))
- `EndDate`: `Union`\[`datetime`, `str`\]
- `InstanceMatchCriteria`: `Literal['open']` (see
  [FleetInstanceMatchCriteriaType](./literals.md#fleetinstancematchcriteriatype))
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[CreateCapacityReservationFleetResultTypeDef](./type_defs.md#createcapacityreservationfleetresulttypedef).

<a id="create_carrier_gateway"></a>

### create_carrier_gateway

Creates a carrier gateway.

Type annotations for `aiobotocore.create_client("ec2").create_carrier_gateway`
method.

Boto3 documentation:
[EC2.Client.create_carrier_gateway](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_carrier_gateway)

Asynchronous method. Use `await create_carrier_gateway(...)` for a synchronous
call.

Arguments mapping described in
[CreateCarrierGatewayRequestRequestTypeDef](./type_defs.md#createcarriergatewayrequestrequesttypedef).

Keyword-only arguments:

- `VpcId`: `str` *(required)*
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `DryRun`: `bool`
- `ClientToken`: `str`

Returns a `Coroutine` for
[CreateCarrierGatewayResultTypeDef](./type_defs.md#createcarriergatewayresulttypedef).

<a id="create_client_vpn_endpoint"></a>

### create_client_vpn_endpoint

Creates a Client VPN endpoint.

Type annotations for
`aiobotocore.create_client("ec2").create_client_vpn_endpoint` method.

Boto3 documentation:
[EC2.Client.create_client_vpn_endpoint](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_client_vpn_endpoint)

Asynchronous method. Use `await create_client_vpn_endpoint(...)` for a
synchronous call.

Arguments mapping described in
[CreateClientVpnEndpointRequestRequestTypeDef](./type_defs.md#createclientvpnendpointrequestrequesttypedef).

Keyword-only arguments:

- `ClientCidrBlock`: `str` *(required)*
- `ServerCertificateArn`: `str` *(required)*
- `AuthenticationOptions`:
  `Sequence`\[[ClientVpnAuthenticationRequestTypeDef](./type_defs.md#clientvpnauthenticationrequesttypedef)\]
  *(required)*
- `ConnectionLogOptions`:
  [ConnectionLogOptionsTypeDef](./type_defs.md#connectionlogoptionstypedef)
  *(required)*
- `DnsServers`: `Sequence`\[`str`\]
- `TransportProtocol`:
  [TransportProtocolType](./literals.md#transportprotocoltype)
- `VpnPort`: `int`
- `Description`: `str`
- `SplitTunnel`: `bool`
- `DryRun`: `bool`
- `ClientToken`: `str`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `SecurityGroupIds`: `Sequence`\[`str`\]
- `VpcId`: `str`
- `SelfServicePortal`:
  [SelfServicePortalType](./literals.md#selfserviceportaltype)
- `ClientConnectOptions`:
  [ClientConnectOptionsTypeDef](./type_defs.md#clientconnectoptionstypedef)

Returns a `Coroutine` for
[CreateClientVpnEndpointResultTypeDef](./type_defs.md#createclientvpnendpointresulttypedef).

<a id="create_client_vpn_route"></a>

### create_client_vpn_route

Adds a route to a network to a Client VPN endpoint.

Type annotations for `aiobotocore.create_client("ec2").create_client_vpn_route`
method.

Boto3 documentation:
[EC2.Client.create_client_vpn_route](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_client_vpn_route)

Asynchronous method. Use `await create_client_vpn_route(...)` for a synchronous
call.

Arguments mapping described in
[CreateClientVpnRouteRequestRequestTypeDef](./type_defs.md#createclientvpnrouterequestrequesttypedef).

Keyword-only arguments:

- `ClientVpnEndpointId`: `str` *(required)*
- `DestinationCidrBlock`: `str` *(required)*
- `TargetVpcSubnetId`: `str` *(required)*
- `Description`: `str`
- `ClientToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[CreateClientVpnRouteResultTypeDef](./type_defs.md#createclientvpnrouteresulttypedef).

<a id="create_customer_gateway"></a>

### create_customer_gateway

Provides information to Amazon Web Services about your VPN customer gateway
device.

Type annotations for `aiobotocore.create_client("ec2").create_customer_gateway`
method.

Boto3 documentation:
[EC2.Client.create_customer_gateway](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_customer_gateway)

Asynchronous method. Use `await create_customer_gateway(...)` for a synchronous
call.

Arguments mapping described in
[CreateCustomerGatewayRequestRequestTypeDef](./type_defs.md#createcustomergatewayrequestrequesttypedef).

Keyword-only arguments:

- `BgpAsn`: `int` *(required)*
- `Type`: `Literal['ipsec.1']` (see
  [GatewayTypeType](./literals.md#gatewaytypetype)) *(required)*
- `PublicIp`: `str`
- `CertificateArn`: `str`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `DeviceName`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[CreateCustomerGatewayResultTypeDef](./type_defs.md#createcustomergatewayresulttypedef).

<a id="create_default_subnet"></a>

### create_default_subnet

Creates a default subnet with a size `/20` IPv4 CIDR block in the specified
Availability Zone in your default VPC.

Type annotations for `aiobotocore.create_client("ec2").create_default_subnet`
method.

Boto3 documentation:
[EC2.Client.create_default_subnet](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_default_subnet)

Asynchronous method. Use `await create_default_subnet(...)` for a synchronous
call.

Arguments mapping described in
[CreateDefaultSubnetRequestRequestTypeDef](./type_defs.md#createdefaultsubnetrequestrequesttypedef).

Keyword-only arguments:

- `AvailabilityZone`: `str` *(required)*
- `DryRun`: `bool`
- `Ipv6Native`: `bool`

Returns a `Coroutine` for
[CreateDefaultSubnetResultTypeDef](./type_defs.md#createdefaultsubnetresulttypedef).

<a id="create_default_vpc"></a>

### create_default_vpc

Creates a default VPC with a size `/16` IPv4 CIDR block and a default subnet in
each Availability Zone.

Type annotations for `aiobotocore.create_client("ec2").create_default_vpc`
method.

Boto3 documentation:
[EC2.Client.create_default_vpc](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_default_vpc)

Asynchronous method. Use `await create_default_vpc(...)` for a synchronous
call.

Arguments mapping described in
[CreateDefaultVpcRequestRequestTypeDef](./type_defs.md#createdefaultvpcrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`

Returns a `Coroutine` for
[CreateDefaultVpcResultTypeDef](./type_defs.md#createdefaultvpcresulttypedef).

<a id="create_dhcp_options"></a>

### create_dhcp_options

Creates a set of DHCP options for your VPC.

Type annotations for `aiobotocore.create_client("ec2").create_dhcp_options`
method.

Boto3 documentation:
[EC2.Client.create_dhcp_options](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_dhcp_options)

Asynchronous method. Use `await create_dhcp_options(...)` for a synchronous
call.

Arguments mapping described in
[CreateDhcpOptionsRequestRequestTypeDef](./type_defs.md#createdhcpoptionsrequestrequesttypedef).

Keyword-only arguments:

- `DhcpConfigurations`:
  `Sequence`\[[NewDhcpConfigurationTypeDef](./type_defs.md#newdhcpconfigurationtypedef)\]
  *(required)*
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[CreateDhcpOptionsResultTypeDef](./type_defs.md#createdhcpoptionsresulttypedef).

<a id="create_egress_only_internet_gateway"></a>

### create_egress_only_internet_gateway

Type annotations for
`aiobotocore.create_client("ec2").create_egress_only_internet_gateway` method.

Boto3 documentation:
[EC2.Client.create_egress_only_internet_gateway](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_egress_only_internet_gateway)

Asynchronous method. Use `await create_egress_only_internet_gateway(...)` for a
synchronous call.

Arguments mapping described in
[CreateEgressOnlyInternetGatewayRequestRequestTypeDef](./type_defs.md#createegressonlyinternetgatewayrequestrequesttypedef).

Keyword-only arguments:

- `VpcId`: `str` *(required)*
- `ClientToken`: `str`
- `DryRun`: `bool`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for
[CreateEgressOnlyInternetGatewayResultTypeDef](./type_defs.md#createegressonlyinternetgatewayresulttypedef).

<a id="create_fleet"></a>

### create_fleet

Launches an EC2 Fleet.

Type annotations for `aiobotocore.create_client("ec2").create_fleet` method.

Boto3 documentation:
[EC2.Client.create_fleet](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_fleet)

Asynchronous method. Use `await create_fleet(...)` for a synchronous call.

Arguments mapping described in
[CreateFleetRequestRequestTypeDef](./type_defs.md#createfleetrequestrequesttypedef).

Keyword-only arguments:

- `LaunchTemplateConfigs`:
  `Sequence`\[[FleetLaunchTemplateConfigRequestTypeDef](./type_defs.md#fleetlaunchtemplateconfigrequesttypedef)\]
  *(required)*
- `TargetCapacitySpecification`:
  [TargetCapacitySpecificationRequestTypeDef](./type_defs.md#targetcapacityspecificationrequesttypedef)
  *(required)*
- `DryRun`: `bool`
- `ClientToken`: `str`
- `SpotOptions`:
  [SpotOptionsRequestTypeDef](./type_defs.md#spotoptionsrequesttypedef)
- `OnDemandOptions`:
  [OnDemandOptionsRequestTypeDef](./type_defs.md#ondemandoptionsrequesttypedef)
- `ExcessCapacityTerminationPolicy`:
  [FleetExcessCapacityTerminationPolicyType](./literals.md#fleetexcesscapacityterminationpolicytype)
- `TerminateInstancesWithExpiration`: `bool`
- `Type`: [FleetTypeType](./literals.md#fleettypetype)
- `ValidFrom`: `Union`\[`datetime`, `str`\]
- `ValidUntil`: `Union`\[`datetime`, `str`\]
- `ReplaceUnhealthyInstances`: `bool`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `Context`: `str`

Returns a `Coroutine` for
[CreateFleetResultTypeDef](./type_defs.md#createfleetresulttypedef).

<a id="create_flow_logs"></a>

### create_flow_logs

Creates one or more flow logs to capture information about IP traffic for a
specific network interface, subnet, or VPC.

Type annotations for `aiobotocore.create_client("ec2").create_flow_logs`
method.

Boto3 documentation:
[EC2.Client.create_flow_logs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_flow_logs)

Asynchronous method. Use `await create_flow_logs(...)` for a synchronous call.

Arguments mapping described in
[CreateFlowLogsRequestRequestTypeDef](./type_defs.md#createflowlogsrequestrequesttypedef).

Keyword-only arguments:

- `ResourceIds`: `Sequence`\[`str`\] *(required)*
- `ResourceType`:
  [FlowLogsResourceTypeType](./literals.md#flowlogsresourcetypetype)
  *(required)*
- `TrafficType`: [TrafficTypeType](./literals.md#traffictypetype) *(required)*
- `DryRun`: `bool`
- `ClientToken`: `str`
- `DeliverLogsPermissionArn`: `str`
- `LogGroupName`: `str`
- `LogDestinationType`:
  [LogDestinationTypeType](./literals.md#logdestinationtypetype)
- `LogDestination`: `str`
- `LogFormat`: `str`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `MaxAggregationInterval`: `int`
- `DestinationOptions`:
  [DestinationOptionsRequestTypeDef](./type_defs.md#destinationoptionsrequesttypedef)

Returns a `Coroutine` for
[CreateFlowLogsResultTypeDef](./type_defs.md#createflowlogsresulttypedef).

<a id="create_fpga_image"></a>

### create_fpga_image

Creates an Amazon FPGA Image (AFI) from the specified design checkpoint (DCP).

Type annotations for `aiobotocore.create_client("ec2").create_fpga_image`
method.

Boto3 documentation:
[EC2.Client.create_fpga_image](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_fpga_image)

Asynchronous method. Use `await create_fpga_image(...)` for a synchronous call.

Arguments mapping described in
[CreateFpgaImageRequestRequestTypeDef](./type_defs.md#createfpgaimagerequestrequesttypedef).

Keyword-only arguments:

- `InputStorageLocation`:
  [StorageLocationTypeDef](./type_defs.md#storagelocationtypedef) *(required)*
- `DryRun`: `bool`
- `LogsStorageLocation`:
  [StorageLocationTypeDef](./type_defs.md#storagelocationtypedef)
- `Description`: `str`
- `Name`: `str`
- `ClientToken`: `str`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for
[CreateFpgaImageResultTypeDef](./type_defs.md#createfpgaimageresulttypedef).

<a id="create_image"></a>

### create_image

Creates an Amazon EBS-backed AMI from an Amazon EBS-backed instance that is
either running or stopped.

Type annotations for `aiobotocore.create_client("ec2").create_image` method.

Boto3 documentation:
[EC2.Client.create_image](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_image)

Asynchronous method. Use `await create_image(...)` for a synchronous call.

Arguments mapping described in
[CreateImageRequestRequestTypeDef](./type_defs.md#createimagerequestrequesttypedef).

Keyword-only arguments:

- `InstanceId`: `str` *(required)*
- `Name`: `str` *(required)*
- `BlockDeviceMappings`:
  `Sequence`\[[BlockDeviceMappingTypeDef](./type_defs.md#blockdevicemappingtypedef)\]
- `Description`: `str`
- `DryRun`: `bool`
- `NoReboot`: `bool`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for
[CreateImageResultTypeDef](./type_defs.md#createimageresulttypedef).

<a id="create_instance_event_window"></a>

### create_instance_event_window

Creates an event window in which scheduled events for the associated Amazon EC2
instances can run.

Type annotations for
`aiobotocore.create_client("ec2").create_instance_event_window` method.

Boto3 documentation:
[EC2.Client.create_instance_event_window](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_instance_event_window)

Asynchronous method. Use `await create_instance_event_window(...)` for a
synchronous call.

Arguments mapping described in
[CreateInstanceEventWindowRequestRequestTypeDef](./type_defs.md#createinstanceeventwindowrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `Name`: `str`
- `TimeRanges`:
  `Sequence`\[[InstanceEventWindowTimeRangeRequestTypeDef](./type_defs.md#instanceeventwindowtimerangerequesttypedef)\]
- `CronExpression`: `str`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for
[CreateInstanceEventWindowResultTypeDef](./type_defs.md#createinstanceeventwindowresulttypedef).

<a id="create_instance_export_task"></a>

### create_instance_export_task

Exports a running or stopped instance to an Amazon S3 bucket.

Type annotations for
`aiobotocore.create_client("ec2").create_instance_export_task` method.

Boto3 documentation:
[EC2.Client.create_instance_export_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_instance_export_task)

Asynchronous method. Use `await create_instance_export_task(...)` for a
synchronous call.

Arguments mapping described in
[CreateInstanceExportTaskRequestRequestTypeDef](./type_defs.md#createinstanceexporttaskrequestrequesttypedef).

Keyword-only arguments:

- `ExportToS3Task`:
  [ExportToS3TaskSpecificationTypeDef](./type_defs.md#exporttos3taskspecificationtypedef)
  *(required)*
- `InstanceId`: `str` *(required)*
- `TargetEnvironment`:
  [ExportEnvironmentType](./literals.md#exportenvironmenttype) *(required)*
- `Description`: `str`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for
[CreateInstanceExportTaskResultTypeDef](./type_defs.md#createinstanceexporttaskresulttypedef).

<a id="create_internet_gateway"></a>

### create_internet_gateway

Creates an internet gateway for use with a VPC.

Type annotations for `aiobotocore.create_client("ec2").create_internet_gateway`
method.

Boto3 documentation:
[EC2.Client.create_internet_gateway](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_internet_gateway)

Asynchronous method. Use `await create_internet_gateway(...)` for a synchronous
call.

Arguments mapping described in
[CreateInternetGatewayRequestRequestTypeDef](./type_defs.md#createinternetgatewayrequestrequesttypedef).

Keyword-only arguments:

- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[CreateInternetGatewayResultTypeDef](./type_defs.md#createinternetgatewayresulttypedef).

<a id="create_ipam"></a>

### create_ipam

Create an IPAM.

Type annotations for `aiobotocore.create_client("ec2").create_ipam` method.

Boto3 documentation:
[EC2.Client.create_ipam](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_ipam)

Asynchronous method. Use `await create_ipam(...)` for a synchronous call.

Arguments mapping described in
[CreateIpamRequestRequestTypeDef](./type_defs.md#createipamrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `Description`: `str`
- `OperatingRegions`:
  `Sequence`\[[AddIpamOperatingRegionTypeDef](./type_defs.md#addipamoperatingregiontypedef)\]
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `ClientToken`: `str`

Returns a `Coroutine` for
[CreateIpamResultTypeDef](./type_defs.md#createipamresulttypedef).

<a id="create_ipam_pool"></a>

### create_ipam_pool

Create an IP address pool for Amazon VPC IP Address Manager (IPAM).

Type annotations for `aiobotocore.create_client("ec2").create_ipam_pool`
method.

Boto3 documentation:
[EC2.Client.create_ipam_pool](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_ipam_pool)

Asynchronous method. Use `await create_ipam_pool(...)` for a synchronous call.

Arguments mapping described in
[CreateIpamPoolRequestRequestTypeDef](./type_defs.md#createipampoolrequestrequesttypedef).

Keyword-only arguments:

- `IpamScopeId`: `str` *(required)*
- `DryRun`: `bool`
- `Locale`: `str`
- `SourceIpamPoolId`: `str`
- `Description`: `str`
- `AddressFamily`: [AddressFamilyType](./literals.md#addressfamilytype)
- `AutoImport`: `bool`
- `PubliclyAdvertisable`: `bool`
- `AllocationMinNetmaskLength`: `int`
- `AllocationMaxNetmaskLength`: `int`
- `AllocationDefaultNetmaskLength`: `int`
- `AllocationResourceTags`:
  `Sequence`\[[RequestIpamResourceTagTypeDef](./type_defs.md#requestipamresourcetagtypedef)\]
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `ClientToken`: `str`
- `AwsService`: `Literal['ec2']` (see
  [IpamPoolAwsServiceType](./literals.md#ipampoolawsservicetype))

Returns a `Coroutine` for
[CreateIpamPoolResultTypeDef](./type_defs.md#createipampoolresulttypedef).

<a id="create_ipam_scope"></a>

### create_ipam_scope

Create an IPAM scope.

Type annotations for `aiobotocore.create_client("ec2").create_ipam_scope`
method.

Boto3 documentation:
[EC2.Client.create_ipam_scope](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_ipam_scope)

Asynchronous method. Use `await create_ipam_scope(...)` for a synchronous call.

Arguments mapping described in
[CreateIpamScopeRequestRequestTypeDef](./type_defs.md#createipamscoperequestrequesttypedef).

Keyword-only arguments:

- `IpamId`: `str` *(required)*
- `DryRun`: `bool`
- `Description`: `str`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `ClientToken`: `str`

Returns a `Coroutine` for
[CreateIpamScopeResultTypeDef](./type_defs.md#createipamscoperesulttypedef).

<a id="create_key_pair"></a>

### create_key_pair

Creates an ED25519 or 2048-bit RSA key pair with the specified name.

Type annotations for `aiobotocore.create_client("ec2").create_key_pair` method.

Boto3 documentation:
[EC2.Client.create_key_pair](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_key_pair)

Asynchronous method. Use `await create_key_pair(...)` for a synchronous call.

Arguments mapping described in
[CreateKeyPairRequestRequestTypeDef](./type_defs.md#createkeypairrequestrequesttypedef).

Keyword-only arguments:

- `KeyName`: `str` *(required)*
- `DryRun`: `bool`
- `KeyType`: [KeyTypeType](./literals.md#keytypetype)
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for [KeyPairTypeDef](./type_defs.md#keypairtypedef).

<a id="create_launch_template"></a>

### create_launch_template

Creates a launch template.

Type annotations for `aiobotocore.create_client("ec2").create_launch_template`
method.

Boto3 documentation:
[EC2.Client.create_launch_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_launch_template)

Asynchronous method. Use `await create_launch_template(...)` for a synchronous
call.

Arguments mapping described in
[CreateLaunchTemplateRequestRequestTypeDef](./type_defs.md#createlaunchtemplaterequestrequesttypedef).

Keyword-only arguments:

- `LaunchTemplateName`: `str` *(required)*
- `LaunchTemplateData`:
  [RequestLaunchTemplateDataTypeDef](./type_defs.md#requestlaunchtemplatedatatypedef)
  *(required)*
- `DryRun`: `bool`
- `ClientToken`: `str`
- `VersionDescription`: `str`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for
[CreateLaunchTemplateResultTypeDef](./type_defs.md#createlaunchtemplateresulttypedef).

<a id="create_launch_template_version"></a>

### create_launch_template_version

Creates a new version for a launch template.

Type annotations for
`aiobotocore.create_client("ec2").create_launch_template_version` method.

Boto3 documentation:
[EC2.Client.create_launch_template_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_launch_template_version)

Asynchronous method. Use `await create_launch_template_version(...)` for a
synchronous call.

Arguments mapping described in
[CreateLaunchTemplateVersionRequestRequestTypeDef](./type_defs.md#createlaunchtemplateversionrequestrequesttypedef).

Keyword-only arguments:

- `LaunchTemplateData`:
  [RequestLaunchTemplateDataTypeDef](./type_defs.md#requestlaunchtemplatedatatypedef)
  *(required)*
- `DryRun`: `bool`
- `ClientToken`: `str`
- `LaunchTemplateId`: `str`
- `LaunchTemplateName`: `str`
- `SourceVersion`: `str`
- `VersionDescription`: `str`

Returns a `Coroutine` for
[CreateLaunchTemplateVersionResultTypeDef](./type_defs.md#createlaunchtemplateversionresulttypedef).

<a id="create_local_gateway_route"></a>

### create_local_gateway_route

Creates a static route for the specified local gateway route table.

Type annotations for
`aiobotocore.create_client("ec2").create_local_gateway_route` method.

Boto3 documentation:
[EC2.Client.create_local_gateway_route](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_local_gateway_route)

Asynchronous method. Use `await create_local_gateway_route(...)` for a
synchronous call.

Arguments mapping described in
[CreateLocalGatewayRouteRequestRequestTypeDef](./type_defs.md#createlocalgatewayrouterequestrequesttypedef).

Keyword-only arguments:

- `DestinationCidrBlock`: `str` *(required)*
- `LocalGatewayRouteTableId`: `str` *(required)*
- `LocalGatewayVirtualInterfaceGroupId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[CreateLocalGatewayRouteResultTypeDef](./type_defs.md#createlocalgatewayrouteresulttypedef).

<a id="create_local_gateway_route_table_vpc_association"></a>

### create_local_gateway_route_table_vpc_association

Associates the specified VPC with the specified local gateway route table.

Type annotations for
`aiobotocore.create_client("ec2").create_local_gateway_route_table_vpc_association`
method.

Boto3 documentation:
[EC2.Client.create_local_gateway_route_table_vpc_association](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_local_gateway_route_table_vpc_association)

Asynchronous method. Use
`await create_local_gateway_route_table_vpc_association(...)` for a synchronous
call.

Arguments mapping described in
[CreateLocalGatewayRouteTableVpcAssociationRequestRequestTypeDef](./type_defs.md#createlocalgatewayroutetablevpcassociationrequestrequesttypedef).

Keyword-only arguments:

- `LocalGatewayRouteTableId`: `str` *(required)*
- `VpcId`: `str` *(required)*
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[CreateLocalGatewayRouteTableVpcAssociationResultTypeDef](./type_defs.md#createlocalgatewayroutetablevpcassociationresulttypedef).

<a id="create_managed_prefix_list"></a>

### create_managed_prefix_list

Creates a managed prefix list.

Type annotations for
`aiobotocore.create_client("ec2").create_managed_prefix_list` method.

Boto3 documentation:
[EC2.Client.create_managed_prefix_list](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_managed_prefix_list)

Asynchronous method. Use `await create_managed_prefix_list(...)` for a
synchronous call.

Arguments mapping described in
[CreateManagedPrefixListRequestRequestTypeDef](./type_defs.md#createmanagedprefixlistrequestrequesttypedef).

Keyword-only arguments:

- `PrefixListName`: `str` *(required)*
- `MaxEntries`: `int` *(required)*
- `AddressFamily`: `str` *(required)*
- `DryRun`: `bool`
- `Entries`:
  `Sequence`\[[AddPrefixListEntryTypeDef](./type_defs.md#addprefixlistentrytypedef)\]
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `ClientToken`: `str`

Returns a `Coroutine` for
[CreateManagedPrefixListResultTypeDef](./type_defs.md#createmanagedprefixlistresulttypedef).

<a id="create_nat_gateway"></a>

### create_nat_gateway

Creates a NAT gateway in the specified subnet.

Type annotations for `aiobotocore.create_client("ec2").create_nat_gateway`
method.

Boto3 documentation:
[EC2.Client.create_nat_gateway](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_nat_gateway)

Asynchronous method. Use `await create_nat_gateway(...)` for a synchronous
call.

Arguments mapping described in
[CreateNatGatewayRequestRequestTypeDef](./type_defs.md#createnatgatewayrequestrequesttypedef).

Keyword-only arguments:

- `SubnetId`: `str` *(required)*
- `AllocationId`: `str`
- `ClientToken`: `str`
- `DryRun`: `bool`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `ConnectivityType`:
  [ConnectivityTypeType](./literals.md#connectivitytypetype)

Returns a `Coroutine` for
[CreateNatGatewayResultTypeDef](./type_defs.md#createnatgatewayresulttypedef).

<a id="create_network_acl"></a>

### create_network_acl

Creates a network ACL in a VPC.

Type annotations for `aiobotocore.create_client("ec2").create_network_acl`
method.

Boto3 documentation:
[EC2.Client.create_network_acl](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_network_acl)

Asynchronous method. Use `await create_network_acl(...)` for a synchronous
call.

Arguments mapping described in
[CreateNetworkAclRequestRequestTypeDef](./type_defs.md#createnetworkaclrequestrequesttypedef).

Keyword-only arguments:

- `VpcId`: `str` *(required)*
- `DryRun`: `bool`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for
[CreateNetworkAclResultTypeDef](./type_defs.md#createnetworkaclresulttypedef).

<a id="create_network_acl_entry"></a>

### create_network_acl_entry

Creates an entry (a rule) in a network ACL with the specified rule number.

Type annotations for
`aiobotocore.create_client("ec2").create_network_acl_entry` method.

Boto3 documentation:
[EC2.Client.create_network_acl_entry](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_network_acl_entry)

Asynchronous method. Use `await create_network_acl_entry(...)` for a
synchronous call.

Arguments mapping described in
[CreateNetworkAclEntryRequestRequestTypeDef](./type_defs.md#createnetworkaclentryrequestrequesttypedef).

Keyword-only arguments:

- `Egress`: `bool` *(required)*
- `NetworkAclId`: `str` *(required)*
- `Protocol`: `str` *(required)*
- `RuleAction`: [RuleActionType](./literals.md#ruleactiontype) *(required)*
- `RuleNumber`: `int` *(required)*
- `CidrBlock`: `str`
- `DryRun`: `bool`
- `IcmpTypeCode`: [IcmpTypeCodeTypeDef](./type_defs.md#icmptypecodetypedef)
- `Ipv6CidrBlock`: `str`
- `PortRange`: [PortRangeTypeDef](./type_defs.md#portrangetypedef)

<a id="create_network_insights_access_scope"></a>

### create_network_insights_access_scope

Creates a Network Access Scope.

Type annotations for
`aiobotocore.create_client("ec2").create_network_insights_access_scope` method.

Boto3 documentation:
[EC2.Client.create_network_insights_access_scope](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_network_insights_access_scope)

Asynchronous method. Use `await create_network_insights_access_scope(...)` for
a synchronous call.

Arguments mapping described in
[CreateNetworkInsightsAccessScopeRequestRequestTypeDef](./type_defs.md#createnetworkinsightsaccessscoperequestrequesttypedef).

Keyword-only arguments:

- `ClientToken`: `str` *(required)*
- `MatchPaths`:
  `Sequence`\[[AccessScopePathRequestTypeDef](./type_defs.md#accessscopepathrequesttypedef)\]
- `ExcludePaths`:
  `Sequence`\[[AccessScopePathRequestTypeDef](./type_defs.md#accessscopepathrequesttypedef)\]
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[CreateNetworkInsightsAccessScopeResultTypeDef](./type_defs.md#createnetworkinsightsaccessscoperesulttypedef).

<a id="create_network_insights_path"></a>

### create_network_insights_path

Creates a path to analyze for reachability.

Type annotations for
`aiobotocore.create_client("ec2").create_network_insights_path` method.

Boto3 documentation:
[EC2.Client.create_network_insights_path](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_network_insights_path)

Asynchronous method. Use `await create_network_insights_path(...)` for a
synchronous call.

Arguments mapping described in
[CreateNetworkInsightsPathRequestRequestTypeDef](./type_defs.md#createnetworkinsightspathrequestrequesttypedef).

Keyword-only arguments:

- `Source`: `str` *(required)*
- `Destination`: `str` *(required)*
- `Protocol`: [ProtocolType](./literals.md#protocoltype) *(required)*
- `ClientToken`: `str` *(required)*
- `SourceIp`: `str`
- `DestinationIp`: `str`
- `DestinationPort`: `int`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[CreateNetworkInsightsPathResultTypeDef](./type_defs.md#createnetworkinsightspathresulttypedef).

<a id="create_network_interface"></a>

### create_network_interface

Creates a network interface in the specified subnet.

Type annotations for
`aiobotocore.create_client("ec2").create_network_interface` method.

Boto3 documentation:
[EC2.Client.create_network_interface](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_network_interface)

Asynchronous method. Use `await create_network_interface(...)` for a
synchronous call.

Arguments mapping described in
[CreateNetworkInterfaceRequestRequestTypeDef](./type_defs.md#createnetworkinterfacerequestrequesttypedef).

Keyword-only arguments:

- `SubnetId`: `str` *(required)*
- `Description`: `str`
- `DryRun`: `bool`
- `Groups`: `Sequence`\[`str`\]
- `Ipv6AddressCount`: `int`
- `Ipv6Addresses`:
  `Sequence`\[[InstanceIpv6AddressTypeDef](./type_defs.md#instanceipv6addresstypedef)\]
- `PrivateIpAddress`: `str`
- `PrivateIpAddresses`:
  `Sequence`\[[PrivateIpAddressSpecificationTypeDef](./type_defs.md#privateipaddressspecificationtypedef)\]
- `SecondaryPrivateIpAddressCount`: `int`
- `Ipv4Prefixes`:
  `Sequence`\[[Ipv4PrefixSpecificationRequestTypeDef](./type_defs.md#ipv4prefixspecificationrequesttypedef)\]
- `Ipv4PrefixCount`: `int`
- `Ipv6Prefixes`:
  `Sequence`\[[Ipv6PrefixSpecificationRequestTypeDef](./type_defs.md#ipv6prefixspecificationrequesttypedef)\]
- `Ipv6PrefixCount`: `int`
- `InterfaceType`:
  [NetworkInterfaceCreationTypeType](./literals.md#networkinterfacecreationtypetype)
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `ClientToken`: `str`

Returns a `Coroutine` for
[CreateNetworkInterfaceResultTypeDef](./type_defs.md#createnetworkinterfaceresulttypedef).

<a id="create_network_interface_permission"></a>

### create_network_interface_permission

Grants an Amazon Web Services-authorized account permission to attach the
specified network interface to an instance in their account.

Type annotations for
`aiobotocore.create_client("ec2").create_network_interface_permission` method.

Boto3 documentation:
[EC2.Client.create_network_interface_permission](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_network_interface_permission)

Asynchronous method. Use `await create_network_interface_permission(...)` for a
synchronous call.

Arguments mapping described in
[CreateNetworkInterfacePermissionRequestRequestTypeDef](./type_defs.md#createnetworkinterfacepermissionrequestrequesttypedef).

Keyword-only arguments:

- `NetworkInterfaceId`: `str` *(required)*
- `Permission`:
  [InterfacePermissionTypeType](./literals.md#interfacepermissiontypetype)
  *(required)*
- `AwsAccountId`: `str`
- `AwsService`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[CreateNetworkInterfacePermissionResultTypeDef](./type_defs.md#createnetworkinterfacepermissionresulttypedef).

<a id="create_placement_group"></a>

### create_placement_group

Creates a placement group in which to launch instances.

Type annotations for `aiobotocore.create_client("ec2").create_placement_group`
method.

Boto3 documentation:
[EC2.Client.create_placement_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_placement_group)

Asynchronous method. Use `await create_placement_group(...)` for a synchronous
call.

Arguments mapping described in
[CreatePlacementGroupRequestRequestTypeDef](./type_defs.md#createplacementgrouprequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `GroupName`: `str`
- `Strategy`: [PlacementStrategyType](./literals.md#placementstrategytype)
- `PartitionCount`: `int`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for
[CreatePlacementGroupResultTypeDef](./type_defs.md#createplacementgroupresulttypedef).

<a id="create_public_ipv4_pool"></a>

### create_public_ipv4_pool

Creates a public IPv4 address pool.

Type annotations for `aiobotocore.create_client("ec2").create_public_ipv4_pool`
method.

Boto3 documentation:
[EC2.Client.create_public_ipv4_pool](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_public_ipv4_pool)

Asynchronous method. Use `await create_public_ipv4_pool(...)` for a synchronous
call.

Arguments mapping described in
[CreatePublicIpv4PoolRequestRequestTypeDef](./type_defs.md#createpublicipv4poolrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for
[CreatePublicIpv4PoolResultTypeDef](./type_defs.md#createpublicipv4poolresulttypedef).

<a id="create_replace_root_volume_task"></a>

### create_replace_root_volume_task

Creates a root volume replacement task for an Amazon EC2 instance.

Type annotations for
`aiobotocore.create_client("ec2").create_replace_root_volume_task` method.

Boto3 documentation:
[EC2.Client.create_replace_root_volume_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_replace_root_volume_task)

Asynchronous method. Use `await create_replace_root_volume_task(...)` for a
synchronous call.

Arguments mapping described in
[CreateReplaceRootVolumeTaskRequestRequestTypeDef](./type_defs.md#createreplacerootvolumetaskrequestrequesttypedef).

Keyword-only arguments:

- `InstanceId`: `str` *(required)*
- `SnapshotId`: `str`
- `ClientToken`: `str`
- `DryRun`: `bool`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for
[CreateReplaceRootVolumeTaskResultTypeDef](./type_defs.md#createreplacerootvolumetaskresulttypedef).

<a id="create_reserved_instances_listing"></a>

### create_reserved_instances_listing

Creates a listing for Amazon EC2 Standard Reserved Instances to be sold in the
Reserved Instance Marketplace.

Type annotations for
`aiobotocore.create_client("ec2").create_reserved_instances_listing` method.

Boto3 documentation:
[EC2.Client.create_reserved_instances_listing](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_reserved_instances_listing)

Asynchronous method. Use `await create_reserved_instances_listing(...)` for a
synchronous call.

Arguments mapping described in
[CreateReservedInstancesListingRequestRequestTypeDef](./type_defs.md#createreservedinstanceslistingrequestrequesttypedef).

Keyword-only arguments:

- `ClientToken`: `str` *(required)*
- `InstanceCount`: `int` *(required)*
- `PriceSchedules`:
  `Sequence`\[[PriceScheduleSpecificationTypeDef](./type_defs.md#priceschedulespecificationtypedef)\]
  *(required)*
- `ReservedInstancesId`: `str` *(required)*

Returns a `Coroutine` for
[CreateReservedInstancesListingResultTypeDef](./type_defs.md#createreservedinstanceslistingresulttypedef).

<a id="create_restore_image_task"></a>

### create_restore_image_task

Starts a task that restores an AMI from an Amazon S3 object that was previously
created by using
[CreateStoreImageTask](https://docs.aws.amazon.com/AWSEC2/latest/APIReference/API_CreateStoreImageTask.html)\_
.

Type annotations for
`aiobotocore.create_client("ec2").create_restore_image_task` method.

Boto3 documentation:
[EC2.Client.create_restore_image_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_restore_image_task)

Asynchronous method. Use `await create_restore_image_task(...)` for a
synchronous call.

Arguments mapping described in
[CreateRestoreImageTaskRequestRequestTypeDef](./type_defs.md#createrestoreimagetaskrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `ObjectKey`: `str` *(required)*
- `Name`: `str`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[CreateRestoreImageTaskResultTypeDef](./type_defs.md#createrestoreimagetaskresulttypedef).

<a id="create_route"></a>

### create_route

Creates a route in a route table within a VPC.

Type annotations for `aiobotocore.create_client("ec2").create_route` method.

Boto3 documentation:
[EC2.Client.create_route](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_route)

Asynchronous method. Use `await create_route(...)` for a synchronous call.

Arguments mapping described in
[CreateRouteRequestRequestTypeDef](./type_defs.md#createrouterequestrequesttypedef).

Keyword-only arguments:

- `RouteTableId`: `str` *(required)*
- `DestinationCidrBlock`: `str`
- `DestinationIpv6CidrBlock`: `str`
- `DestinationPrefixListId`: `str`
- `DryRun`: `bool`
- `VpcEndpointId`: `str`
- `EgressOnlyInternetGatewayId`: `str`
- `GatewayId`: `str`
- `InstanceId`: `str`
- `NatGatewayId`: `str`
- `TransitGatewayId`: `str`
- `LocalGatewayId`: `str`
- `CarrierGatewayId`: `str`
- `NetworkInterfaceId`: `str`
- `VpcPeeringConnectionId`: `str`
- `CoreNetworkArn`: `str`

Returns a `Coroutine` for
[CreateRouteResultTypeDef](./type_defs.md#createrouteresulttypedef).

<a id="create_route_table"></a>

### create_route_table

Creates a route table for the specified VPC.

Type annotations for `aiobotocore.create_client("ec2").create_route_table`
method.

Boto3 documentation:
[EC2.Client.create_route_table](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_route_table)

Asynchronous method. Use `await create_route_table(...)` for a synchronous
call.

Arguments mapping described in
[CreateRouteTableRequestRequestTypeDef](./type_defs.md#createroutetablerequestrequesttypedef).

Keyword-only arguments:

- `VpcId`: `str` *(required)*
- `DryRun`: `bool`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for
[CreateRouteTableResultTypeDef](./type_defs.md#createroutetableresulttypedef).

<a id="create_security_group"></a>

### create_security_group

Creates a security group.

Type annotations for `aiobotocore.create_client("ec2").create_security_group`
method.

Boto3 documentation:
[EC2.Client.create_security_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_security_group)

Asynchronous method. Use `await create_security_group(...)` for a synchronous
call.

Arguments mapping described in
[CreateSecurityGroupRequestRequestTypeDef](./type_defs.md#createsecuritygrouprequestrequesttypedef).

Keyword-only arguments:

- `Description`: `str` *(required)*
- `GroupName`: `str` *(required)*
- `VpcId`: `str`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[CreateSecurityGroupResultTypeDef](./type_defs.md#createsecuritygroupresulttypedef).

<a id="create_snapshot"></a>

### create_snapshot

Creates a snapshot of an EBS volume and stores it in Amazon S3.

Type annotations for `aiobotocore.create_client("ec2").create_snapshot` method.

Boto3 documentation:
[EC2.Client.create_snapshot](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_snapshot)

Asynchronous method. Use `await create_snapshot(...)` for a synchronous call.

Arguments mapping described in
[CreateSnapshotRequestRequestTypeDef](./type_defs.md#createsnapshotrequestrequesttypedef).

Keyword-only arguments:

- `VolumeId`: `str` *(required)*
- `Description`: `str`
- `OutpostArn`: `str`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[SnapshotResponseMetadataTypeDef](./type_defs.md#snapshotresponsemetadatatypedef).

<a id="create_snapshots"></a>

### create_snapshots

Creates crash-consistent snapshots of multiple EBS volumes and stores the data
in S3.

Type annotations for `aiobotocore.create_client("ec2").create_snapshots`
method.

Boto3 documentation:
[EC2.Client.create_snapshots](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_snapshots)

Asynchronous method. Use `await create_snapshots(...)` for a synchronous call.

Arguments mapping described in
[CreateSnapshotsRequestRequestTypeDef](./type_defs.md#createsnapshotsrequestrequesttypedef).

Keyword-only arguments:

- `InstanceSpecification`:
  [InstanceSpecificationTypeDef](./type_defs.md#instancespecificationtypedef)
  *(required)*
- `Description`: `str`
- `OutpostArn`: `str`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `DryRun`: `bool`
- `CopyTagsFromSource`: `Literal['volume']` (see
  [CopyTagsFromSourceType](./literals.md#copytagsfromsourcetype))

Returns a `Coroutine` for
[CreateSnapshotsResultTypeDef](./type_defs.md#createsnapshotsresulttypedef).

<a id="create_spot_datafeed_subscription"></a>

### create_spot_datafeed_subscription

Creates a data feed for Spot Instances, enabling you to view Spot Instance
usage logs.

Type annotations for
`aiobotocore.create_client("ec2").create_spot_datafeed_subscription` method.

Boto3 documentation:
[EC2.Client.create_spot_datafeed_subscription](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_spot_datafeed_subscription)

Asynchronous method. Use `await create_spot_datafeed_subscription(...)` for a
synchronous call.

Arguments mapping described in
[CreateSpotDatafeedSubscriptionRequestRequestTypeDef](./type_defs.md#createspotdatafeedsubscriptionrequestrequesttypedef).

Keyword-only arguments:

- `Bucket`: `str` *(required)*
- `DryRun`: `bool`
- `Prefix`: `str`

Returns a `Coroutine` for
[CreateSpotDatafeedSubscriptionResultTypeDef](./type_defs.md#createspotdatafeedsubscriptionresulttypedef).

<a id="create_store_image_task"></a>

### create_store_image_task

Stores an AMI as a single object in an Amazon S3 bucket.

Type annotations for `aiobotocore.create_client("ec2").create_store_image_task`
method.

Boto3 documentation:
[EC2.Client.create_store_image_task](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_store_image_task)

Asynchronous method. Use `await create_store_image_task(...)` for a synchronous
call.

Arguments mapping described in
[CreateStoreImageTaskRequestRequestTypeDef](./type_defs.md#createstoreimagetaskrequestrequesttypedef).

Keyword-only arguments:

- `ImageId`: `str` *(required)*
- `Bucket`: `str` *(required)*
- `S3ObjectTags`:
  `Sequence`\[[S3ObjectTagTypeDef](./type_defs.md#s3objecttagtypedef)\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[CreateStoreImageTaskResultTypeDef](./type_defs.md#createstoreimagetaskresulttypedef).

<a id="create_subnet"></a>

### create_subnet

Creates a subnet in a specified VPC.

Type annotations for `aiobotocore.create_client("ec2").create_subnet` method.

Boto3 documentation:
[EC2.Client.create_subnet](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_subnet)

Asynchronous method. Use `await create_subnet(...)` for a synchronous call.

Arguments mapping described in
[CreateSubnetRequestRequestTypeDef](./type_defs.md#createsubnetrequestrequesttypedef).

Keyword-only arguments:

- `VpcId`: `str` *(required)*
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `AvailabilityZone`: `str`
- `AvailabilityZoneId`: `str`
- `CidrBlock`: `str`
- `Ipv6CidrBlock`: `str`
- `OutpostArn`: `str`
- `DryRun`: `bool`
- `Ipv6Native`: `bool`

Returns a `Coroutine` for
[CreateSubnetResultTypeDef](./type_defs.md#createsubnetresulttypedef).

<a id="create_subnet_cidr_reservation"></a>

### create_subnet_cidr_reservation

Creates a subnet CIDR reservation.

Type annotations for
`aiobotocore.create_client("ec2").create_subnet_cidr_reservation` method.

Boto3 documentation:
[EC2.Client.create_subnet_cidr_reservation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_subnet_cidr_reservation)

Asynchronous method. Use `await create_subnet_cidr_reservation(...)` for a
synchronous call.

Arguments mapping described in
[CreateSubnetCidrReservationRequestRequestTypeDef](./type_defs.md#createsubnetcidrreservationrequestrequesttypedef).

Keyword-only arguments:

- `SubnetId`: `str` *(required)*
- `Cidr`: `str` *(required)*
- `ReservationType`:
  [SubnetCidrReservationTypeType](./literals.md#subnetcidrreservationtypetype)
  *(required)*
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `Description`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[CreateSubnetCidrReservationResultTypeDef](./type_defs.md#createsubnetcidrreservationresulttypedef).

<a id="create_tags"></a>

### create_tags

Adds or overwrites only the specified tags for the specified Amazon EC2
resource or resources.

Type annotations for `aiobotocore.create_client("ec2").create_tags` method.

Boto3 documentation:
[EC2.Client.create_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_tags)

Asynchronous method. Use `await create_tags(...)` for a synchronous call.

Arguments mapping described in
[CreateTagsRequestRequestTypeDef](./type_defs.md#createtagsrequestrequesttypedef).

Keyword-only arguments:

- `Resources`: `Sequence`\[`Any`\] *(required)*
- `Tags`: `Optional`\[`Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]\]
  *(required)*
- `DryRun`: `bool`

<a id="create_traffic_mirror_filter"></a>

### create_traffic_mirror_filter

Creates a Traffic Mirror filter.

Type annotations for
`aiobotocore.create_client("ec2").create_traffic_mirror_filter` method.

Boto3 documentation:
[EC2.Client.create_traffic_mirror_filter](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_traffic_mirror_filter)

Asynchronous method. Use `await create_traffic_mirror_filter(...)` for a
synchronous call.

Arguments mapping described in
[CreateTrafficMirrorFilterRequestRequestTypeDef](./type_defs.md#createtrafficmirrorfilterrequestrequesttypedef).

Keyword-only arguments:

- `Description`: `str`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `DryRun`: `bool`
- `ClientToken`: `str`

Returns a `Coroutine` for
[CreateTrafficMirrorFilterResultTypeDef](./type_defs.md#createtrafficmirrorfilterresulttypedef).

<a id="create_traffic_mirror_filter_rule"></a>

### create_traffic_mirror_filter_rule

Creates a Traffic Mirror filter rule.

Type annotations for
`aiobotocore.create_client("ec2").create_traffic_mirror_filter_rule` method.

Boto3 documentation:
[EC2.Client.create_traffic_mirror_filter_rule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_traffic_mirror_filter_rule)

Asynchronous method. Use `await create_traffic_mirror_filter_rule(...)` for a
synchronous call.

Arguments mapping described in
[CreateTrafficMirrorFilterRuleRequestRequestTypeDef](./type_defs.md#createtrafficmirrorfilterrulerequestrequesttypedef).

Keyword-only arguments:

- `TrafficMirrorFilterId`: `str` *(required)*
- `TrafficDirection`:
  [TrafficDirectionType](./literals.md#trafficdirectiontype) *(required)*
- `RuleNumber`: `int` *(required)*
- `RuleAction`:
  [TrafficMirrorRuleActionType](./literals.md#trafficmirrorruleactiontype)
  *(required)*
- `DestinationCidrBlock`: `str` *(required)*
- `SourceCidrBlock`: `str` *(required)*
- `DestinationPortRange`:
  [TrafficMirrorPortRangeRequestTypeDef](./type_defs.md#trafficmirrorportrangerequesttypedef)
- `SourcePortRange`:
  [TrafficMirrorPortRangeRequestTypeDef](./type_defs.md#trafficmirrorportrangerequesttypedef)
- `Protocol`: `int`
- `Description`: `str`
- `DryRun`: `bool`
- `ClientToken`: `str`

Returns a `Coroutine` for
[CreateTrafficMirrorFilterRuleResultTypeDef](./type_defs.md#createtrafficmirrorfilterruleresulttypedef).

<a id="create_traffic_mirror_session"></a>

### create_traffic_mirror_session

Creates a Traffic Mirror session.

Type annotations for
`aiobotocore.create_client("ec2").create_traffic_mirror_session` method.

Boto3 documentation:
[EC2.Client.create_traffic_mirror_session](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_traffic_mirror_session)

Asynchronous method. Use `await create_traffic_mirror_session(...)` for a
synchronous call.

Arguments mapping described in
[CreateTrafficMirrorSessionRequestRequestTypeDef](./type_defs.md#createtrafficmirrorsessionrequestrequesttypedef).

Keyword-only arguments:

- `NetworkInterfaceId`: `str` *(required)*
- `TrafficMirrorTargetId`: `str` *(required)*
- `TrafficMirrorFilterId`: `str` *(required)*
- `SessionNumber`: `int` *(required)*
- `PacketLength`: `int`
- `VirtualNetworkId`: `int`
- `Description`: `str`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `DryRun`: `bool`
- `ClientToken`: `str`

Returns a `Coroutine` for
[CreateTrafficMirrorSessionResultTypeDef](./type_defs.md#createtrafficmirrorsessionresulttypedef).

<a id="create_traffic_mirror_target"></a>

### create_traffic_mirror_target

Creates a target for your Traffic Mirror session.

Type annotations for
`aiobotocore.create_client("ec2").create_traffic_mirror_target` method.

Boto3 documentation:
[EC2.Client.create_traffic_mirror_target](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_traffic_mirror_target)

Asynchronous method. Use `await create_traffic_mirror_target(...)` for a
synchronous call.

Arguments mapping described in
[CreateTrafficMirrorTargetRequestRequestTypeDef](./type_defs.md#createtrafficmirrortargetrequestrequesttypedef).

Keyword-only arguments:

- `NetworkInterfaceId`: `str`
- `NetworkLoadBalancerArn`: `str`
- `Description`: `str`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `DryRun`: `bool`
- `ClientToken`: `str`

Returns a `Coroutine` for
[CreateTrafficMirrorTargetResultTypeDef](./type_defs.md#createtrafficmirrortargetresulttypedef).

<a id="create_transit_gateway"></a>

### create_transit_gateway

Creates a transit gateway.

Type annotations for `aiobotocore.create_client("ec2").create_transit_gateway`
method.

Boto3 documentation:
[EC2.Client.create_transit_gateway](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_transit_gateway)

Asynchronous method. Use `await create_transit_gateway(...)` for a synchronous
call.

Arguments mapping described in
[CreateTransitGatewayRequestRequestTypeDef](./type_defs.md#createtransitgatewayrequestrequesttypedef).

Keyword-only arguments:

- `Description`: `str`
- `Options`:
  [TransitGatewayRequestOptionsTypeDef](./type_defs.md#transitgatewayrequestoptionstypedef)
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[CreateTransitGatewayResultTypeDef](./type_defs.md#createtransitgatewayresulttypedef).

<a id="create_transit_gateway_connect"></a>

### create_transit_gateway_connect

Creates a Connect attachment from a specified transit gateway attachment.

Type annotations for
`aiobotocore.create_client("ec2").create_transit_gateway_connect` method.

Boto3 documentation:
[EC2.Client.create_transit_gateway_connect](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_transit_gateway_connect)

Asynchronous method. Use `await create_transit_gateway_connect(...)` for a
synchronous call.

Arguments mapping described in
[CreateTransitGatewayConnectRequestRequestTypeDef](./type_defs.md#createtransitgatewayconnectrequestrequesttypedef).

Keyword-only arguments:

- `TransportTransitGatewayAttachmentId`: `str` *(required)*
- `Options`:
  [CreateTransitGatewayConnectRequestOptionsTypeDef](./type_defs.md#createtransitgatewayconnectrequestoptionstypedef)
  *(required)*
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[CreateTransitGatewayConnectResultTypeDef](./type_defs.md#createtransitgatewayconnectresulttypedef).

<a id="create_transit_gateway_connect_peer"></a>

### create_transit_gateway_connect_peer

Creates a Connect peer for a specified transit gateway Connect attachment
between a transit gateway and an appliance.

Type annotations for
`aiobotocore.create_client("ec2").create_transit_gateway_connect_peer` method.

Boto3 documentation:
[EC2.Client.create_transit_gateway_connect_peer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_transit_gateway_connect_peer)

Asynchronous method. Use `await create_transit_gateway_connect_peer(...)` for a
synchronous call.

Arguments mapping described in
[CreateTransitGatewayConnectPeerRequestRequestTypeDef](./type_defs.md#createtransitgatewayconnectpeerrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayAttachmentId`: `str` *(required)*
- `PeerAddress`: `str` *(required)*
- `InsideCidrBlocks`: `Sequence`\[`str`\] *(required)*
- `TransitGatewayAddress`: `str`
- `BgpOptions`:
  [TransitGatewayConnectRequestBgpOptionsTypeDef](./type_defs.md#transitgatewayconnectrequestbgpoptionstypedef)
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[CreateTransitGatewayConnectPeerResultTypeDef](./type_defs.md#createtransitgatewayconnectpeerresulttypedef).

<a id="create_transit_gateway_multicast_domain"></a>

### create_transit_gateway_multicast_domain

Creates a multicast domain using the specified transit gateway.

Type annotations for
`aiobotocore.create_client("ec2").create_transit_gateway_multicast_domain`
method.

Boto3 documentation:
[EC2.Client.create_transit_gateway_multicast_domain](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_transit_gateway_multicast_domain)

Asynchronous method. Use `await create_transit_gateway_multicast_domain(...)`
for a synchronous call.

Arguments mapping described in
[CreateTransitGatewayMulticastDomainRequestRequestTypeDef](./type_defs.md#createtransitgatewaymulticastdomainrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayId`: `str` *(required)*
- `Options`:
  [CreateTransitGatewayMulticastDomainRequestOptionsTypeDef](./type_defs.md#createtransitgatewaymulticastdomainrequestoptionstypedef)
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[CreateTransitGatewayMulticastDomainResultTypeDef](./type_defs.md#createtransitgatewaymulticastdomainresulttypedef).

<a id="create_transit_gateway_peering_attachment"></a>

### create_transit_gateway_peering_attachment

Requests a transit gateway peering attachment between the specified transit
gateway (requester) and a peer transit gateway (accepter).

Type annotations for
`aiobotocore.create_client("ec2").create_transit_gateway_peering_attachment`
method.

Boto3 documentation:
[EC2.Client.create_transit_gateway_peering_attachment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_transit_gateway_peering_attachment)

Asynchronous method. Use `await create_transit_gateway_peering_attachment(...)`
for a synchronous call.

Arguments mapping described in
[CreateTransitGatewayPeeringAttachmentRequestRequestTypeDef](./type_defs.md#createtransitgatewaypeeringattachmentrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayId`: `str` *(required)*
- `PeerTransitGatewayId`: `str` *(required)*
- `PeerAccountId`: `str` *(required)*
- `PeerRegion`: `str` *(required)*
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[CreateTransitGatewayPeeringAttachmentResultTypeDef](./type_defs.md#createtransitgatewaypeeringattachmentresulttypedef).

<a id="create_transit_gateway_prefix_list_reference"></a>

### create_transit_gateway_prefix_list_reference

Creates a reference (route) to a prefix list in a specified transit gateway
route table.

Type annotations for
`aiobotocore.create_client("ec2").create_transit_gateway_prefix_list_reference`
method.

Boto3 documentation:
[EC2.Client.create_transit_gateway_prefix_list_reference](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_transit_gateway_prefix_list_reference)

Asynchronous method. Use
`await create_transit_gateway_prefix_list_reference(...)` for a synchronous
call.

Arguments mapping described in
[CreateTransitGatewayPrefixListReferenceRequestRequestTypeDef](./type_defs.md#createtransitgatewayprefixlistreferencerequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayRouteTableId`: `str` *(required)*
- `PrefixListId`: `str` *(required)*
- `TransitGatewayAttachmentId`: `str`
- `Blackhole`: `bool`
- `DryRun`: `bool`

Returns a `Coroutine` for
[CreateTransitGatewayPrefixListReferenceResultTypeDef](./type_defs.md#createtransitgatewayprefixlistreferenceresulttypedef).

<a id="create_transit_gateway_route"></a>

### create_transit_gateway_route

Creates a static route for the specified transit gateway route table.

Type annotations for
`aiobotocore.create_client("ec2").create_transit_gateway_route` method.

Boto3 documentation:
[EC2.Client.create_transit_gateway_route](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_transit_gateway_route)

Asynchronous method. Use `await create_transit_gateway_route(...)` for a
synchronous call.

Arguments mapping described in
[CreateTransitGatewayRouteRequestRequestTypeDef](./type_defs.md#createtransitgatewayrouterequestrequesttypedef).

Keyword-only arguments:

- `DestinationCidrBlock`: `str` *(required)*
- `TransitGatewayRouteTableId`: `str` *(required)*
- `TransitGatewayAttachmentId`: `str`
- `Blackhole`: `bool`
- `DryRun`: `bool`

Returns a `Coroutine` for
[CreateTransitGatewayRouteResultTypeDef](./type_defs.md#createtransitgatewayrouteresulttypedef).

<a id="create_transit_gateway_route_table"></a>

### create_transit_gateway_route_table

Creates a route table for the specified transit gateway.

Type annotations for
`aiobotocore.create_client("ec2").create_transit_gateway_route_table` method.

Boto3 documentation:
[EC2.Client.create_transit_gateway_route_table](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_transit_gateway_route_table)

Asynchronous method. Use `await create_transit_gateway_route_table(...)` for a
synchronous call.

Arguments mapping described in
[CreateTransitGatewayRouteTableRequestRequestTypeDef](./type_defs.md#createtransitgatewayroutetablerequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayId`: `str` *(required)*
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[CreateTransitGatewayRouteTableResultTypeDef](./type_defs.md#createtransitgatewayroutetableresulttypedef).

<a id="create_transit_gateway_vpc_attachment"></a>

### create_transit_gateway_vpc_attachment

Attaches the specified VPC to the specified transit gateway.

Type annotations for
`aiobotocore.create_client("ec2").create_transit_gateway_vpc_attachment`
method.

Boto3 documentation:
[EC2.Client.create_transit_gateway_vpc_attachment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_transit_gateway_vpc_attachment)

Asynchronous method. Use `await create_transit_gateway_vpc_attachment(...)` for
a synchronous call.

Arguments mapping described in
[CreateTransitGatewayVpcAttachmentRequestRequestTypeDef](./type_defs.md#createtransitgatewayvpcattachmentrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayId`: `str` *(required)*
- `VpcId`: `str` *(required)*
- `SubnetIds`: `Sequence`\[`str`\] *(required)*
- `Options`:
  [CreateTransitGatewayVpcAttachmentRequestOptionsTypeDef](./type_defs.md#createtransitgatewayvpcattachmentrequestoptionstypedef)
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[CreateTransitGatewayVpcAttachmentResultTypeDef](./type_defs.md#createtransitgatewayvpcattachmentresulttypedef).

<a id="create_volume"></a>

### create_volume

Creates an EBS volume that can be attached to an instance in the same
Availability Zone.

Type annotations for `aiobotocore.create_client("ec2").create_volume` method.

Boto3 documentation:
[EC2.Client.create_volume](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_volume)

Asynchronous method. Use `await create_volume(...)` for a synchronous call.

Arguments mapping described in
[CreateVolumeRequestRequestTypeDef](./type_defs.md#createvolumerequestrequesttypedef).

Keyword-only arguments:

- `AvailabilityZone`: `str` *(required)*
- `Encrypted`: `bool`
- `Iops`: `int`
- `KmsKeyId`: `str`
- `OutpostArn`: `str`
- `Size`: `int`
- `SnapshotId`: `str`
- `VolumeType`: [VolumeTypeType](./literals.md#volumetypetype)
- `DryRun`: `bool`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `MultiAttachEnabled`: `bool`
- `Throughput`: `int`
- `ClientToken`: `str`

Returns a `Coroutine` for
[VolumeResponseMetadataTypeDef](./type_defs.md#volumeresponsemetadatatypedef).

<a id="create_vpc"></a>

### create_vpc

Creates a VPC with the specified IPv4 CIDR block.

Type annotations for `aiobotocore.create_client("ec2").create_vpc` method.

Boto3 documentation:
[EC2.Client.create_vpc](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_vpc)

Asynchronous method. Use `await create_vpc(...)` for a synchronous call.

Arguments mapping described in
[CreateVpcRequestRequestTypeDef](./type_defs.md#createvpcrequestrequesttypedef).

Keyword-only arguments:

- `CidrBlock`: `str`
- `AmazonProvidedIpv6CidrBlock`: `bool`
- `Ipv6Pool`: `str`
- `Ipv6CidrBlock`: `str`
- `Ipv4IpamPoolId`: `str`
- `Ipv4NetmaskLength`: `int`
- `Ipv6IpamPoolId`: `str`
- `Ipv6NetmaskLength`: `int`
- `DryRun`: `bool`
- `InstanceTenancy`: [TenancyType](./literals.md#tenancytype)
- `Ipv6CidrBlockNetworkBorderGroup`: `str`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for
[CreateVpcResultTypeDef](./type_defs.md#createvpcresulttypedef).

<a id="create_vpc_endpoint"></a>

### create_vpc_endpoint

Creates a VPC endpoint for a specified service.

Type annotations for `aiobotocore.create_client("ec2").create_vpc_endpoint`
method.

Boto3 documentation:
[EC2.Client.create_vpc_endpoint](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_vpc_endpoint)

Asynchronous method. Use `await create_vpc_endpoint(...)` for a synchronous
call.

Arguments mapping described in
[CreateVpcEndpointRequestRequestTypeDef](./type_defs.md#createvpcendpointrequestrequesttypedef).

Keyword-only arguments:

- `VpcId`: `str` *(required)*
- `ServiceName`: `str` *(required)*
- `DryRun`: `bool`
- `VpcEndpointType`: [VpcEndpointTypeType](./literals.md#vpcendpointtypetype)
- `PolicyDocument`: `str`
- `RouteTableIds`: `Sequence`\[`str`\]
- `SubnetIds`: `Sequence`\[`str`\]
- `SecurityGroupIds`: `Sequence`\[`str`\]
- `ClientToken`: `str`
- `PrivateDnsEnabled`: `bool`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for
[CreateVpcEndpointResultTypeDef](./type_defs.md#createvpcendpointresulttypedef).

<a id="create_vpc_endpoint_connection_notification"></a>

### create_vpc_endpoint_connection_notification

Creates a connection notification for a specified VPC endpoint or VPC endpoint
service.

Type annotations for
`aiobotocore.create_client("ec2").create_vpc_endpoint_connection_notification`
method.

Boto3 documentation:
[EC2.Client.create_vpc_endpoint_connection_notification](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_vpc_endpoint_connection_notification)

Asynchronous method. Use
`await create_vpc_endpoint_connection_notification(...)` for a synchronous
call.

Arguments mapping described in
[CreateVpcEndpointConnectionNotificationRequestRequestTypeDef](./type_defs.md#createvpcendpointconnectionnotificationrequestrequesttypedef).

Keyword-only arguments:

- `ConnectionNotificationArn`: `str` *(required)*
- `ConnectionEvents`: `Sequence`\[`str`\] *(required)*
- `DryRun`: `bool`
- `ServiceId`: `str`
- `VpcEndpointId`: `str`
- `ClientToken`: `str`

Returns a `Coroutine` for
[CreateVpcEndpointConnectionNotificationResultTypeDef](./type_defs.md#createvpcendpointconnectionnotificationresulttypedef).

<a id="create_vpc_endpoint_service_configuration"></a>

### create_vpc_endpoint_service_configuration

Creates a VPC endpoint service configuration to which service consumers (Amazon
Web Services accounts, IAM users, and IAM roles) can connect.

Type annotations for
`aiobotocore.create_client("ec2").create_vpc_endpoint_service_configuration`
method.

Boto3 documentation:
[EC2.Client.create_vpc_endpoint_service_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_vpc_endpoint_service_configuration)

Asynchronous method. Use `await create_vpc_endpoint_service_configuration(...)`
for a synchronous call.

Arguments mapping described in
[CreateVpcEndpointServiceConfigurationRequestRequestTypeDef](./type_defs.md#createvpcendpointserviceconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `AcceptanceRequired`: `bool`
- `PrivateDnsName`: `str`
- `NetworkLoadBalancerArns`: `Sequence`\[`str`\]
- `GatewayLoadBalancerArns`: `Sequence`\[`str`\]
- `ClientToken`: `str`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for
[CreateVpcEndpointServiceConfigurationResultTypeDef](./type_defs.md#createvpcendpointserviceconfigurationresulttypedef).

<a id="create_vpc_peering_connection"></a>

### create_vpc_peering_connection

Requests a VPC peering connection between two VPCs: a requester VPC that you
own and an accepter VPC with which to create the connection.

Type annotations for
`aiobotocore.create_client("ec2").create_vpc_peering_connection` method.

Boto3 documentation:
[EC2.Client.create_vpc_peering_connection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_vpc_peering_connection)

Asynchronous method. Use `await create_vpc_peering_connection(...)` for a
synchronous call.

Arguments mapping described in
[CreateVpcPeeringConnectionRequestRequestTypeDef](./type_defs.md#createvpcpeeringconnectionrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `PeerOwnerId`: `str`
- `PeerVpcId`: `str`
- `VpcId`: `str`
- `PeerRegion`: `str`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for
[CreateVpcPeeringConnectionResultTypeDef](./type_defs.md#createvpcpeeringconnectionresulttypedef).

<a id="create_vpn_connection"></a>

### create_vpn_connection

Creates a VPN connection between an existing virtual private gateway or transit
gateway and a customer gateway.

Type annotations for `aiobotocore.create_client("ec2").create_vpn_connection`
method.

Boto3 documentation:
[EC2.Client.create_vpn_connection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_vpn_connection)

Asynchronous method. Use `await create_vpn_connection(...)` for a synchronous
call.

Arguments mapping described in
[CreateVpnConnectionRequestRequestTypeDef](./type_defs.md#createvpnconnectionrequestrequesttypedef).

Keyword-only arguments:

- `CustomerGatewayId`: `str` *(required)*
- `Type`: `str` *(required)*
- `VpnGatewayId`: `str`
- `TransitGatewayId`: `str`
- `DryRun`: `bool`
- `Options`:
  [VpnConnectionOptionsSpecificationTypeDef](./type_defs.md#vpnconnectionoptionsspecificationtypedef)
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for
[CreateVpnConnectionResultTypeDef](./type_defs.md#createvpnconnectionresulttypedef).

<a id="create_vpn_connection_route"></a>

### create_vpn_connection_route

Creates a static route associated with a VPN connection between an existing
virtual private gateway and a VPN customer gateway.

Type annotations for
`aiobotocore.create_client("ec2").create_vpn_connection_route` method.

Boto3 documentation:
[EC2.Client.create_vpn_connection_route](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_vpn_connection_route)

Asynchronous method. Use `await create_vpn_connection_route(...)` for a
synchronous call.

Arguments mapping described in
[CreateVpnConnectionRouteRequestRequestTypeDef](./type_defs.md#createvpnconnectionrouterequestrequesttypedef).

Keyword-only arguments:

- `DestinationCidrBlock`: `str` *(required)*
- `VpnConnectionId`: `str` *(required)*

<a id="create_vpn_gateway"></a>

### create_vpn_gateway

Creates a virtual private gateway.

Type annotations for `aiobotocore.create_client("ec2").create_vpn_gateway`
method.

Boto3 documentation:
[EC2.Client.create_vpn_gateway](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.create_vpn_gateway)

Asynchronous method. Use `await create_vpn_gateway(...)` for a synchronous
call.

Arguments mapping described in
[CreateVpnGatewayRequestRequestTypeDef](./type_defs.md#createvpngatewayrequestrequesttypedef).

Keyword-only arguments:

- `Type`: `Literal['ipsec.1']` (see
  [GatewayTypeType](./literals.md#gatewaytypetype)) *(required)*
- `AvailabilityZone`: `str`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `AmazonSideAsn`: `int`
- `DryRun`: `bool`

Returns a `Coroutine` for
[CreateVpnGatewayResultTypeDef](./type_defs.md#createvpngatewayresulttypedef).

<a id="delete_carrier_gateway"></a>

### delete_carrier_gateway

Deletes a carrier gateway.

Type annotations for `aiobotocore.create_client("ec2").delete_carrier_gateway`
method.

Boto3 documentation:
[EC2.Client.delete_carrier_gateway](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_carrier_gateway)

Asynchronous method. Use `await delete_carrier_gateway(...)` for a synchronous
call.

Arguments mapping described in
[DeleteCarrierGatewayRequestRequestTypeDef](./type_defs.md#deletecarriergatewayrequestrequesttypedef).

Keyword-only arguments:

- `CarrierGatewayId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteCarrierGatewayResultTypeDef](./type_defs.md#deletecarriergatewayresulttypedef).

<a id="delete_client_vpn_endpoint"></a>

### delete_client_vpn_endpoint

Deletes the specified Client VPN endpoint.

Type annotations for
`aiobotocore.create_client("ec2").delete_client_vpn_endpoint` method.

Boto3 documentation:
[EC2.Client.delete_client_vpn_endpoint](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_client_vpn_endpoint)

Asynchronous method. Use `await delete_client_vpn_endpoint(...)` for a
synchronous call.

Arguments mapping described in
[DeleteClientVpnEndpointRequestRequestTypeDef](./type_defs.md#deleteclientvpnendpointrequestrequesttypedef).

Keyword-only arguments:

- `ClientVpnEndpointId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteClientVpnEndpointResultTypeDef](./type_defs.md#deleteclientvpnendpointresulttypedef).

<a id="delete_client_vpn_route"></a>

### delete_client_vpn_route

Deletes a route from a Client VPN endpoint.

Type annotations for `aiobotocore.create_client("ec2").delete_client_vpn_route`
method.

Boto3 documentation:
[EC2.Client.delete_client_vpn_route](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_client_vpn_route)

Asynchronous method. Use `await delete_client_vpn_route(...)` for a synchronous
call.

Arguments mapping described in
[DeleteClientVpnRouteRequestRequestTypeDef](./type_defs.md#deleteclientvpnrouterequestrequesttypedef).

Keyword-only arguments:

- `ClientVpnEndpointId`: `str` *(required)*
- `DestinationCidrBlock`: `str` *(required)*
- `TargetVpcSubnetId`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteClientVpnRouteResultTypeDef](./type_defs.md#deleteclientvpnrouteresulttypedef).

<a id="delete_customer_gateway"></a>

### delete_customer_gateway

Deletes the specified customer gateway.

Type annotations for `aiobotocore.create_client("ec2").delete_customer_gateway`
method.

Boto3 documentation:
[EC2.Client.delete_customer_gateway](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_customer_gateway)

Asynchronous method. Use `await delete_customer_gateway(...)` for a synchronous
call.

Arguments mapping described in
[DeleteCustomerGatewayRequestRequestTypeDef](./type_defs.md#deletecustomergatewayrequestrequesttypedef).

Keyword-only arguments:

- `CustomerGatewayId`: `str` *(required)*
- `DryRun`: `bool`

<a id="delete_dhcp_options"></a>

### delete_dhcp_options

Deletes the specified set of DHCP options.

Type annotations for `aiobotocore.create_client("ec2").delete_dhcp_options`
method.

Boto3 documentation:
[EC2.Client.delete_dhcp_options](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_dhcp_options)

Asynchronous method. Use `await delete_dhcp_options(...)` for a synchronous
call.

Arguments mapping described in
[DeleteDhcpOptionsRequestRequestTypeDef](./type_defs.md#deletedhcpoptionsrequestrequesttypedef).

Keyword-only arguments:

- `DhcpOptionsId`: `str` *(required)*
- `DryRun`: `bool`

<a id="delete_egress_only_internet_gateway"></a>

### delete_egress_only_internet_gateway

Deletes an egress-only internet gateway.

Type annotations for
`aiobotocore.create_client("ec2").delete_egress_only_internet_gateway` method.

Boto3 documentation:
[EC2.Client.delete_egress_only_internet_gateway](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_egress_only_internet_gateway)

Asynchronous method. Use `await delete_egress_only_internet_gateway(...)` for a
synchronous call.

Arguments mapping described in
[DeleteEgressOnlyInternetGatewayRequestRequestTypeDef](./type_defs.md#deleteegressonlyinternetgatewayrequestrequesttypedef).

Keyword-only arguments:

- `EgressOnlyInternetGatewayId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteEgressOnlyInternetGatewayResultTypeDef](./type_defs.md#deleteegressonlyinternetgatewayresulttypedef).

<a id="delete_fleets"></a>

### delete_fleets

Deletes the specified EC2 Fleet.

Type annotations for `aiobotocore.create_client("ec2").delete_fleets` method.

Boto3 documentation:
[EC2.Client.delete_fleets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_fleets)

Asynchronous method. Use `await delete_fleets(...)` for a synchronous call.

Arguments mapping described in
[DeleteFleetsRequestRequestTypeDef](./type_defs.md#deletefleetsrequestrequesttypedef).

Keyword-only arguments:

- `FleetIds`: `Sequence`\[`str`\] *(required)*
- `TerminateInstances`: `bool` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteFleetsResultTypeDef](./type_defs.md#deletefleetsresulttypedef).

<a id="delete_flow_logs"></a>

### delete_flow_logs

Deletes one or more flow logs.

Type annotations for `aiobotocore.create_client("ec2").delete_flow_logs`
method.

Boto3 documentation:
[EC2.Client.delete_flow_logs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_flow_logs)

Asynchronous method. Use `await delete_flow_logs(...)` for a synchronous call.

Arguments mapping described in
[DeleteFlowLogsRequestRequestTypeDef](./type_defs.md#deleteflowlogsrequestrequesttypedef).

Keyword-only arguments:

- `FlowLogIds`: `Sequence`\[`str`\] *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteFlowLogsResultTypeDef](./type_defs.md#deleteflowlogsresulttypedef).

<a id="delete_fpga_image"></a>

### delete_fpga_image

Deletes the specified Amazon FPGA Image (AFI).

Type annotations for `aiobotocore.create_client("ec2").delete_fpga_image`
method.

Boto3 documentation:
[EC2.Client.delete_fpga_image](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_fpga_image)

Asynchronous method. Use `await delete_fpga_image(...)` for a synchronous call.

Arguments mapping described in
[DeleteFpgaImageRequestRequestTypeDef](./type_defs.md#deletefpgaimagerequestrequesttypedef).

Keyword-only arguments:

- `FpgaImageId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteFpgaImageResultTypeDef](./type_defs.md#deletefpgaimageresulttypedef).

<a id="delete_instance_event_window"></a>

### delete_instance_event_window

Deletes the specified event window.

Type annotations for
`aiobotocore.create_client("ec2").delete_instance_event_window` method.

Boto3 documentation:
[EC2.Client.delete_instance_event_window](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_instance_event_window)

Asynchronous method. Use `await delete_instance_event_window(...)` for a
synchronous call.

Arguments mapping described in
[DeleteInstanceEventWindowRequestRequestTypeDef](./type_defs.md#deleteinstanceeventwindowrequestrequesttypedef).

Keyword-only arguments:

- `InstanceEventWindowId`: `str` *(required)*
- `DryRun`: `bool`
- `ForceDelete`: `bool`

Returns a `Coroutine` for
[DeleteInstanceEventWindowResultTypeDef](./type_defs.md#deleteinstanceeventwindowresulttypedef).

<a id="delete_internet_gateway"></a>

### delete_internet_gateway

Deletes the specified internet gateway.

Type annotations for `aiobotocore.create_client("ec2").delete_internet_gateway`
method.

Boto3 documentation:
[EC2.Client.delete_internet_gateway](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_internet_gateway)

Asynchronous method. Use `await delete_internet_gateway(...)` for a synchronous
call.

Arguments mapping described in
[DeleteInternetGatewayRequestRequestTypeDef](./type_defs.md#deleteinternetgatewayrequestrequesttypedef).

Keyword-only arguments:

- `InternetGatewayId`: `str` *(required)*
- `DryRun`: `bool`

<a id="delete_ipam"></a>

### delete_ipam

Delete an IPAM.

Type annotations for `aiobotocore.create_client("ec2").delete_ipam` method.

Boto3 documentation:
[EC2.Client.delete_ipam](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_ipam)

Asynchronous method. Use `await delete_ipam(...)` for a synchronous call.

Arguments mapping described in
[DeleteIpamRequestRequestTypeDef](./type_defs.md#deleteipamrequestrequesttypedef).

Keyword-only arguments:

- `IpamId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteIpamResultTypeDef](./type_defs.md#deleteipamresulttypedef).

<a id="delete_ipam_pool"></a>

### delete_ipam_pool

Delete an IPAM pool.

Type annotations for `aiobotocore.create_client("ec2").delete_ipam_pool`
method.

Boto3 documentation:
[EC2.Client.delete_ipam_pool](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_ipam_pool)

Asynchronous method. Use `await delete_ipam_pool(...)` for a synchronous call.

Arguments mapping described in
[DeleteIpamPoolRequestRequestTypeDef](./type_defs.md#deleteipampoolrequestrequesttypedef).

Keyword-only arguments:

- `IpamPoolId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteIpamPoolResultTypeDef](./type_defs.md#deleteipampoolresulttypedef).

<a id="delete_ipam_scope"></a>

### delete_ipam_scope

Delete the scope for an IPAM.

Type annotations for `aiobotocore.create_client("ec2").delete_ipam_scope`
method.

Boto3 documentation:
[EC2.Client.delete_ipam_scope](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_ipam_scope)

Asynchronous method. Use `await delete_ipam_scope(...)` for a synchronous call.

Arguments mapping described in
[DeleteIpamScopeRequestRequestTypeDef](./type_defs.md#deleteipamscoperequestrequesttypedef).

Keyword-only arguments:

- `IpamScopeId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteIpamScopeResultTypeDef](./type_defs.md#deleteipamscoperesulttypedef).

<a id="delete_key_pair"></a>

### delete_key_pair

Deletes the specified key pair, by removing the public key from Amazon EC2.

Type annotations for `aiobotocore.create_client("ec2").delete_key_pair` method.

Boto3 documentation:
[EC2.Client.delete_key_pair](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_key_pair)

Asynchronous method. Use `await delete_key_pair(...)` for a synchronous call.

Arguments mapping described in
[DeleteKeyPairRequestRequestTypeDef](./type_defs.md#deletekeypairrequestrequesttypedef).

Keyword-only arguments:

- `KeyName`: `str`
- `KeyPairId`: `str`
- `DryRun`: `bool`

<a id="delete_launch_template"></a>

### delete_launch_template

Deletes a launch template.

Type annotations for `aiobotocore.create_client("ec2").delete_launch_template`
method.

Boto3 documentation:
[EC2.Client.delete_launch_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_launch_template)

Asynchronous method. Use `await delete_launch_template(...)` for a synchronous
call.

Arguments mapping described in
[DeleteLaunchTemplateRequestRequestTypeDef](./type_defs.md#deletelaunchtemplaterequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `LaunchTemplateId`: `str`
- `LaunchTemplateName`: `str`

Returns a `Coroutine` for
[DeleteLaunchTemplateResultTypeDef](./type_defs.md#deletelaunchtemplateresulttypedef).

<a id="delete_launch_template_versions"></a>

### delete_launch_template_versions

Deletes one or more versions of a launch template.

Type annotations for
`aiobotocore.create_client("ec2").delete_launch_template_versions` method.

Boto3 documentation:
[EC2.Client.delete_launch_template_versions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_launch_template_versions)

Asynchronous method. Use `await delete_launch_template_versions(...)` for a
synchronous call.

Arguments mapping described in
[DeleteLaunchTemplateVersionsRequestRequestTypeDef](./type_defs.md#deletelaunchtemplateversionsrequestrequesttypedef).

Keyword-only arguments:

- `Versions`: `Sequence`\[`str`\] *(required)*
- `DryRun`: `bool`
- `LaunchTemplateId`: `str`
- `LaunchTemplateName`: `str`

Returns a `Coroutine` for
[DeleteLaunchTemplateVersionsResultTypeDef](./type_defs.md#deletelaunchtemplateversionsresulttypedef).

<a id="delete_local_gateway_route"></a>

### delete_local_gateway_route

Deletes the specified route from the specified local gateway route table.

Type annotations for
`aiobotocore.create_client("ec2").delete_local_gateway_route` method.

Boto3 documentation:
[EC2.Client.delete_local_gateway_route](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_local_gateway_route)

Asynchronous method. Use `await delete_local_gateway_route(...)` for a
synchronous call.

Arguments mapping described in
[DeleteLocalGatewayRouteRequestRequestTypeDef](./type_defs.md#deletelocalgatewayrouterequestrequesttypedef).

Keyword-only arguments:

- `DestinationCidrBlock`: `str` *(required)*
- `LocalGatewayRouteTableId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteLocalGatewayRouteResultTypeDef](./type_defs.md#deletelocalgatewayrouteresulttypedef).

<a id="delete_local_gateway_route_table_vpc_association"></a>

### delete_local_gateway_route_table_vpc_association

Deletes the specified association between a VPC and local gateway route table.

Type annotations for
`aiobotocore.create_client("ec2").delete_local_gateway_route_table_vpc_association`
method.

Boto3 documentation:
[EC2.Client.delete_local_gateway_route_table_vpc_association](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_local_gateway_route_table_vpc_association)

Asynchronous method. Use
`await delete_local_gateway_route_table_vpc_association(...)` for a synchronous
call.

Arguments mapping described in
[DeleteLocalGatewayRouteTableVpcAssociationRequestRequestTypeDef](./type_defs.md#deletelocalgatewayroutetablevpcassociationrequestrequesttypedef).

Keyword-only arguments:

- `LocalGatewayRouteTableVpcAssociationId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteLocalGatewayRouteTableVpcAssociationResultTypeDef](./type_defs.md#deletelocalgatewayroutetablevpcassociationresulttypedef).

<a id="delete_managed_prefix_list"></a>

### delete_managed_prefix_list

Deletes the specified managed prefix list.

Type annotations for
`aiobotocore.create_client("ec2").delete_managed_prefix_list` method.

Boto3 documentation:
[EC2.Client.delete_managed_prefix_list](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_managed_prefix_list)

Asynchronous method. Use `await delete_managed_prefix_list(...)` for a
synchronous call.

Arguments mapping described in
[DeleteManagedPrefixListRequestRequestTypeDef](./type_defs.md#deletemanagedprefixlistrequestrequesttypedef).

Keyword-only arguments:

- `PrefixListId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteManagedPrefixListResultTypeDef](./type_defs.md#deletemanagedprefixlistresulttypedef).

<a id="delete_nat_gateway"></a>

### delete_nat_gateway

Deletes the specified NAT gateway.

Type annotations for `aiobotocore.create_client("ec2").delete_nat_gateway`
method.

Boto3 documentation:
[EC2.Client.delete_nat_gateway](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_nat_gateway)

Asynchronous method. Use `await delete_nat_gateway(...)` for a synchronous
call.

Arguments mapping described in
[DeleteNatGatewayRequestRequestTypeDef](./type_defs.md#deletenatgatewayrequestrequesttypedef).

Keyword-only arguments:

- `NatGatewayId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteNatGatewayResultTypeDef](./type_defs.md#deletenatgatewayresulttypedef).

<a id="delete_network_acl"></a>

### delete_network_acl

Deletes the specified network ACL.

Type annotations for `aiobotocore.create_client("ec2").delete_network_acl`
method.

Boto3 documentation:
[EC2.Client.delete_network_acl](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_network_acl)

Asynchronous method. Use `await delete_network_acl(...)` for a synchronous
call.

Arguments mapping described in
[DeleteNetworkAclRequestRequestTypeDef](./type_defs.md#deletenetworkaclrequestrequesttypedef).

Keyword-only arguments:

- `NetworkAclId`: `str` *(required)*
- `DryRun`: `bool`

<a id="delete_network_acl_entry"></a>

### delete_network_acl_entry

Deletes the specified ingress or egress entry (rule) from the specified network
ACL.

Type annotations for
`aiobotocore.create_client("ec2").delete_network_acl_entry` method.

Boto3 documentation:
[EC2.Client.delete_network_acl_entry](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_network_acl_entry)

Asynchronous method. Use `await delete_network_acl_entry(...)` for a
synchronous call.

Arguments mapping described in
[DeleteNetworkAclEntryRequestRequestTypeDef](./type_defs.md#deletenetworkaclentryrequestrequesttypedef).

Keyword-only arguments:

- `Egress`: `bool` *(required)*
- `NetworkAclId`: `str` *(required)*
- `RuleNumber`: `int` *(required)*
- `DryRun`: `bool`

<a id="delete_network_insights_access_scope"></a>

### delete_network_insights_access_scope

Deletes the specified Network Access Scope.

Type annotations for
`aiobotocore.create_client("ec2").delete_network_insights_access_scope` method.

Boto3 documentation:
[EC2.Client.delete_network_insights_access_scope](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_network_insights_access_scope)

Asynchronous method. Use `await delete_network_insights_access_scope(...)` for
a synchronous call.

Arguments mapping described in
[DeleteNetworkInsightsAccessScopeRequestRequestTypeDef](./type_defs.md#deletenetworkinsightsaccessscoperequestrequesttypedef).

Keyword-only arguments:

- `NetworkInsightsAccessScopeId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteNetworkInsightsAccessScopeResultTypeDef](./type_defs.md#deletenetworkinsightsaccessscoperesulttypedef).

<a id="delete_network_insights_access_scope_analysis"></a>

### delete_network_insights_access_scope_analysis

Deletes the specified Network Access Scope analysis.

Type annotations for
`aiobotocore.create_client("ec2").delete_network_insights_access_scope_analysis`
method.

Boto3 documentation:
[EC2.Client.delete_network_insights_access_scope_analysis](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_network_insights_access_scope_analysis)

Asynchronous method. Use
`await delete_network_insights_access_scope_analysis(...)` for a synchronous
call.

Arguments mapping described in
[DeleteNetworkInsightsAccessScopeAnalysisRequestRequestTypeDef](./type_defs.md#deletenetworkinsightsaccessscopeanalysisrequestrequesttypedef).

Keyword-only arguments:

- `NetworkInsightsAccessScopeAnalysisId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteNetworkInsightsAccessScopeAnalysisResultTypeDef](./type_defs.md#deletenetworkinsightsaccessscopeanalysisresulttypedef).

<a id="delete_network_insights_analysis"></a>

### delete_network_insights_analysis

Deletes the specified network insights analysis.

Type annotations for
`aiobotocore.create_client("ec2").delete_network_insights_analysis` method.

Boto3 documentation:
[EC2.Client.delete_network_insights_analysis](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_network_insights_analysis)

Asynchronous method. Use `await delete_network_insights_analysis(...)` for a
synchronous call.

Arguments mapping described in
[DeleteNetworkInsightsAnalysisRequestRequestTypeDef](./type_defs.md#deletenetworkinsightsanalysisrequestrequesttypedef).

Keyword-only arguments:

- `NetworkInsightsAnalysisId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteNetworkInsightsAnalysisResultTypeDef](./type_defs.md#deletenetworkinsightsanalysisresulttypedef).

<a id="delete_network_insights_path"></a>

### delete_network_insights_path

Deletes the specified path.

Type annotations for
`aiobotocore.create_client("ec2").delete_network_insights_path` method.

Boto3 documentation:
[EC2.Client.delete_network_insights_path](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_network_insights_path)

Asynchronous method. Use `await delete_network_insights_path(...)` for a
synchronous call.

Arguments mapping described in
[DeleteNetworkInsightsPathRequestRequestTypeDef](./type_defs.md#deletenetworkinsightspathrequestrequesttypedef).

Keyword-only arguments:

- `NetworkInsightsPathId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteNetworkInsightsPathResultTypeDef](./type_defs.md#deletenetworkinsightspathresulttypedef).

<a id="delete_network_interface"></a>

### delete_network_interface

Deletes the specified network interface.

Type annotations for
`aiobotocore.create_client("ec2").delete_network_interface` method.

Boto3 documentation:
[EC2.Client.delete_network_interface](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_network_interface)

Asynchronous method. Use `await delete_network_interface(...)` for a
synchronous call.

Arguments mapping described in
[DeleteNetworkInterfaceRequestRequestTypeDef](./type_defs.md#deletenetworkinterfacerequestrequesttypedef).

Keyword-only arguments:

- `NetworkInterfaceId`: `str` *(required)*
- `DryRun`: `bool`

<a id="delete_network_interface_permission"></a>

### delete_network_interface_permission

Deletes a permission for a network interface.

Type annotations for
`aiobotocore.create_client("ec2").delete_network_interface_permission` method.

Boto3 documentation:
[EC2.Client.delete_network_interface_permission](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_network_interface_permission)

Asynchronous method. Use `await delete_network_interface_permission(...)` for a
synchronous call.

Arguments mapping described in
[DeleteNetworkInterfacePermissionRequestRequestTypeDef](./type_defs.md#deletenetworkinterfacepermissionrequestrequesttypedef).

Keyword-only arguments:

- `NetworkInterfacePermissionId`: `str` *(required)*
- `Force`: `bool`
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteNetworkInterfacePermissionResultTypeDef](./type_defs.md#deletenetworkinterfacepermissionresulttypedef).

<a id="delete_placement_group"></a>

### delete_placement_group

Deletes the specified placement group.

Type annotations for `aiobotocore.create_client("ec2").delete_placement_group`
method.

Boto3 documentation:
[EC2.Client.delete_placement_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_placement_group)

Asynchronous method. Use `await delete_placement_group(...)` for a synchronous
call.

Arguments mapping described in
[DeletePlacementGroupRequestRequestTypeDef](./type_defs.md#deleteplacementgrouprequestrequesttypedef).

Keyword-only arguments:

- `GroupName`: `str` *(required)*
- `DryRun`: `bool`

<a id="delete_public_ipv4_pool"></a>

### delete_public_ipv4_pool

Delete a public IPv4 pool.

Type annotations for `aiobotocore.create_client("ec2").delete_public_ipv4_pool`
method.

Boto3 documentation:
[EC2.Client.delete_public_ipv4_pool](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_public_ipv4_pool)

Asynchronous method. Use `await delete_public_ipv4_pool(...)` for a synchronous
call.

Arguments mapping described in
[DeletePublicIpv4PoolRequestRequestTypeDef](./type_defs.md#deletepublicipv4poolrequestrequesttypedef).

Keyword-only arguments:

- `PoolId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeletePublicIpv4PoolResultTypeDef](./type_defs.md#deletepublicipv4poolresulttypedef).

<a id="delete_queued_reserved_instances"></a>

### delete_queued_reserved_instances

Deletes the queued purchases for the specified Reserved Instances.

Type annotations for
`aiobotocore.create_client("ec2").delete_queued_reserved_instances` method.

Boto3 documentation:
[EC2.Client.delete_queued_reserved_instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_queued_reserved_instances)

Asynchronous method. Use `await delete_queued_reserved_instances(...)` for a
synchronous call.

Arguments mapping described in
[DeleteQueuedReservedInstancesRequestRequestTypeDef](./type_defs.md#deletequeuedreservedinstancesrequestrequesttypedef).

Keyword-only arguments:

- `ReservedInstancesIds`: `Sequence`\[`str`\] *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteQueuedReservedInstancesResultTypeDef](./type_defs.md#deletequeuedreservedinstancesresulttypedef).

<a id="delete_route"></a>

### delete_route

Deletes the specified route from the specified route table.

Type annotations for `aiobotocore.create_client("ec2").delete_route` method.

Boto3 documentation:
[EC2.Client.delete_route](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_route)

Asynchronous method. Use `await delete_route(...)` for a synchronous call.

Arguments mapping described in
[DeleteRouteRequestRequestTypeDef](./type_defs.md#deleterouterequestrequesttypedef).

Keyword-only arguments:

- `RouteTableId`: `str` *(required)*
- `DestinationCidrBlock`: `str`
- `DestinationIpv6CidrBlock`: `str`
- `DestinationPrefixListId`: `str`
- `DryRun`: `bool`

<a id="delete_route_table"></a>

### delete_route_table

Deletes the specified route table.

Type annotations for `aiobotocore.create_client("ec2").delete_route_table`
method.

Boto3 documentation:
[EC2.Client.delete_route_table](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_route_table)

Asynchronous method. Use `await delete_route_table(...)` for a synchronous
call.

Arguments mapping described in
[DeleteRouteTableRequestRequestTypeDef](./type_defs.md#deleteroutetablerequestrequesttypedef).

Keyword-only arguments:

- `RouteTableId`: `str` *(required)*
- `DryRun`: `bool`

<a id="delete_security_group"></a>

### delete_security_group

Deletes a security group.

Type annotations for `aiobotocore.create_client("ec2").delete_security_group`
method.

Boto3 documentation:
[EC2.Client.delete_security_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_security_group)

Asynchronous method. Use `await delete_security_group(...)` for a synchronous
call.

Arguments mapping described in
[DeleteSecurityGroupRequestRequestTypeDef](./type_defs.md#deletesecuritygrouprequestrequesttypedef).

Keyword-only arguments:

- `GroupId`: `str`
- `GroupName`: `str`
- `DryRun`: `bool`

<a id="delete_snapshot"></a>

### delete_snapshot

Deletes the specified snapshot.

Type annotations for `aiobotocore.create_client("ec2").delete_snapshot` method.

Boto3 documentation:
[EC2.Client.delete_snapshot](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_snapshot)

Asynchronous method. Use `await delete_snapshot(...)` for a synchronous call.

Arguments mapping described in
[DeleteSnapshotRequestRequestTypeDef](./type_defs.md#deletesnapshotrequestrequesttypedef).

Keyword-only arguments:

- `SnapshotId`: `str` *(required)*
- `DryRun`: `bool`

<a id="delete_spot_datafeed_subscription"></a>

### delete_spot_datafeed_subscription

Deletes the data feed for Spot Instances.

Type annotations for
`aiobotocore.create_client("ec2").delete_spot_datafeed_subscription` method.

Boto3 documentation:
[EC2.Client.delete_spot_datafeed_subscription](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_spot_datafeed_subscription)

Asynchronous method. Use `await delete_spot_datafeed_subscription(...)` for a
synchronous call.

Arguments mapping described in
[DeleteSpotDatafeedSubscriptionRequestRequestTypeDef](./type_defs.md#deletespotdatafeedsubscriptionrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`

<a id="delete_subnet"></a>

### delete_subnet

Deletes the specified subnet.

Type annotations for `aiobotocore.create_client("ec2").delete_subnet` method.

Boto3 documentation:
[EC2.Client.delete_subnet](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_subnet)

Asynchronous method. Use `await delete_subnet(...)` for a synchronous call.

Arguments mapping described in
[DeleteSubnetRequestRequestTypeDef](./type_defs.md#deletesubnetrequestrequesttypedef).

Keyword-only arguments:

- `SubnetId`: `str` *(required)*
- `DryRun`: `bool`

<a id="delete_subnet_cidr_reservation"></a>

### delete_subnet_cidr_reservation

Deletes a subnet CIDR reservation.

Type annotations for
`aiobotocore.create_client("ec2").delete_subnet_cidr_reservation` method.

Boto3 documentation:
[EC2.Client.delete_subnet_cidr_reservation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_subnet_cidr_reservation)

Asynchronous method. Use `await delete_subnet_cidr_reservation(...)` for a
synchronous call.

Arguments mapping described in
[DeleteSubnetCidrReservationRequestRequestTypeDef](./type_defs.md#deletesubnetcidrreservationrequestrequesttypedef).

Keyword-only arguments:

- `SubnetCidrReservationId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteSubnetCidrReservationResultTypeDef](./type_defs.md#deletesubnetcidrreservationresulttypedef).

<a id="delete_tags"></a>

### delete_tags

Deletes the specified set of tags from the specified set of resources.

Type annotations for `aiobotocore.create_client("ec2").delete_tags` method.

Boto3 documentation:
[EC2.Client.delete_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_tags)

Asynchronous method. Use `await delete_tags(...)` for a synchronous call.

Arguments mapping described in
[DeleteTagsRequestRequestTypeDef](./type_defs.md#deletetagsrequestrequesttypedef).

Keyword-only arguments:

- `Resources`: `Sequence`\[`Any`\] *(required)*
- `DryRun`: `bool`
- `Tags`: `Optional`\[`Sequence`\[[TagTypeDef](./type_defs.md#tagtypedef)\]\]

<a id="delete_traffic_mirror_filter"></a>

### delete_traffic_mirror_filter

Deletes the specified Traffic Mirror filter.

Type annotations for
`aiobotocore.create_client("ec2").delete_traffic_mirror_filter` method.

Boto3 documentation:
[EC2.Client.delete_traffic_mirror_filter](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_traffic_mirror_filter)

Asynchronous method. Use `await delete_traffic_mirror_filter(...)` for a
synchronous call.

Arguments mapping described in
[DeleteTrafficMirrorFilterRequestRequestTypeDef](./type_defs.md#deletetrafficmirrorfilterrequestrequesttypedef).

Keyword-only arguments:

- `TrafficMirrorFilterId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteTrafficMirrorFilterResultTypeDef](./type_defs.md#deletetrafficmirrorfilterresulttypedef).

<a id="delete_traffic_mirror_filter_rule"></a>

### delete_traffic_mirror_filter_rule

Deletes the specified Traffic Mirror rule.

Type annotations for
`aiobotocore.create_client("ec2").delete_traffic_mirror_filter_rule` method.

Boto3 documentation:
[EC2.Client.delete_traffic_mirror_filter_rule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_traffic_mirror_filter_rule)

Asynchronous method. Use `await delete_traffic_mirror_filter_rule(...)` for a
synchronous call.

Arguments mapping described in
[DeleteTrafficMirrorFilterRuleRequestRequestTypeDef](./type_defs.md#deletetrafficmirrorfilterrulerequestrequesttypedef).

Keyword-only arguments:

- `TrafficMirrorFilterRuleId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteTrafficMirrorFilterRuleResultTypeDef](./type_defs.md#deletetrafficmirrorfilterruleresulttypedef).

<a id="delete_traffic_mirror_session"></a>

### delete_traffic_mirror_session

Deletes the specified Traffic Mirror session.

Type annotations for
`aiobotocore.create_client("ec2").delete_traffic_mirror_session` method.

Boto3 documentation:
[EC2.Client.delete_traffic_mirror_session](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_traffic_mirror_session)

Asynchronous method. Use `await delete_traffic_mirror_session(...)` for a
synchronous call.

Arguments mapping described in
[DeleteTrafficMirrorSessionRequestRequestTypeDef](./type_defs.md#deletetrafficmirrorsessionrequestrequesttypedef).

Keyword-only arguments:

- `TrafficMirrorSessionId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteTrafficMirrorSessionResultTypeDef](./type_defs.md#deletetrafficmirrorsessionresulttypedef).

<a id="delete_traffic_mirror_target"></a>

### delete_traffic_mirror_target

Deletes the specified Traffic Mirror target.

Type annotations for
`aiobotocore.create_client("ec2").delete_traffic_mirror_target` method.

Boto3 documentation:
[EC2.Client.delete_traffic_mirror_target](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_traffic_mirror_target)

Asynchronous method. Use `await delete_traffic_mirror_target(...)` for a
synchronous call.

Arguments mapping described in
[DeleteTrafficMirrorTargetRequestRequestTypeDef](./type_defs.md#deletetrafficmirrortargetrequestrequesttypedef).

Keyword-only arguments:

- `TrafficMirrorTargetId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteTrafficMirrorTargetResultTypeDef](./type_defs.md#deletetrafficmirrortargetresulttypedef).

<a id="delete_transit_gateway"></a>

### delete_transit_gateway

Deletes the specified transit gateway.

Type annotations for `aiobotocore.create_client("ec2").delete_transit_gateway`
method.

Boto3 documentation:
[EC2.Client.delete_transit_gateway](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_transit_gateway)

Asynchronous method. Use `await delete_transit_gateway(...)` for a synchronous
call.

Arguments mapping described in
[DeleteTransitGatewayRequestRequestTypeDef](./type_defs.md#deletetransitgatewayrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteTransitGatewayResultTypeDef](./type_defs.md#deletetransitgatewayresulttypedef).

<a id="delete_transit_gateway_connect"></a>

### delete_transit_gateway_connect

Deletes the specified Connect attachment.

Type annotations for
`aiobotocore.create_client("ec2").delete_transit_gateway_connect` method.

Boto3 documentation:
[EC2.Client.delete_transit_gateway_connect](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_transit_gateway_connect)

Asynchronous method. Use `await delete_transit_gateway_connect(...)` for a
synchronous call.

Arguments mapping described in
[DeleteTransitGatewayConnectRequestRequestTypeDef](./type_defs.md#deletetransitgatewayconnectrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayAttachmentId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteTransitGatewayConnectResultTypeDef](./type_defs.md#deletetransitgatewayconnectresulttypedef).

<a id="delete_transit_gateway_connect_peer"></a>

### delete_transit_gateway_connect_peer

Deletes the specified Connect peer.

Type annotations for
`aiobotocore.create_client("ec2").delete_transit_gateway_connect_peer` method.

Boto3 documentation:
[EC2.Client.delete_transit_gateway_connect_peer](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_transit_gateway_connect_peer)

Asynchronous method. Use `await delete_transit_gateway_connect_peer(...)` for a
synchronous call.

Arguments mapping described in
[DeleteTransitGatewayConnectPeerRequestRequestTypeDef](./type_defs.md#deletetransitgatewayconnectpeerrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayConnectPeerId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteTransitGatewayConnectPeerResultTypeDef](./type_defs.md#deletetransitgatewayconnectpeerresulttypedef).

<a id="delete_transit_gateway_multicast_domain"></a>

### delete_transit_gateway_multicast_domain

Deletes the specified transit gateway multicast domain.

Type annotations for
`aiobotocore.create_client("ec2").delete_transit_gateway_multicast_domain`
method.

Boto3 documentation:
[EC2.Client.delete_transit_gateway_multicast_domain](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_transit_gateway_multicast_domain)

Asynchronous method. Use `await delete_transit_gateway_multicast_domain(...)`
for a synchronous call.

Arguments mapping described in
[DeleteTransitGatewayMulticastDomainRequestRequestTypeDef](./type_defs.md#deletetransitgatewaymulticastdomainrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayMulticastDomainId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteTransitGatewayMulticastDomainResultTypeDef](./type_defs.md#deletetransitgatewaymulticastdomainresulttypedef).

<a id="delete_transit_gateway_peering_attachment"></a>

### delete_transit_gateway_peering_attachment

Deletes a transit gateway peering attachment.

Type annotations for
`aiobotocore.create_client("ec2").delete_transit_gateway_peering_attachment`
method.

Boto3 documentation:
[EC2.Client.delete_transit_gateway_peering_attachment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_transit_gateway_peering_attachment)

Asynchronous method. Use `await delete_transit_gateway_peering_attachment(...)`
for a synchronous call.

Arguments mapping described in
[DeleteTransitGatewayPeeringAttachmentRequestRequestTypeDef](./type_defs.md#deletetransitgatewaypeeringattachmentrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayAttachmentId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteTransitGatewayPeeringAttachmentResultTypeDef](./type_defs.md#deletetransitgatewaypeeringattachmentresulttypedef).

<a id="delete_transit_gateway_prefix_list_reference"></a>

### delete_transit_gateway_prefix_list_reference

Deletes a reference (route) to a prefix list in a specified transit gateway
route table.

Type annotations for
`aiobotocore.create_client("ec2").delete_transit_gateway_prefix_list_reference`
method.

Boto3 documentation:
[EC2.Client.delete_transit_gateway_prefix_list_reference](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_transit_gateway_prefix_list_reference)

Asynchronous method. Use
`await delete_transit_gateway_prefix_list_reference(...)` for a synchronous
call.

Arguments mapping described in
[DeleteTransitGatewayPrefixListReferenceRequestRequestTypeDef](./type_defs.md#deletetransitgatewayprefixlistreferencerequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayRouteTableId`: `str` *(required)*
- `PrefixListId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteTransitGatewayPrefixListReferenceResultTypeDef](./type_defs.md#deletetransitgatewayprefixlistreferenceresulttypedef).

<a id="delete_transit_gateway_route"></a>

### delete_transit_gateway_route

Deletes the specified route from the specified transit gateway route table.

Type annotations for
`aiobotocore.create_client("ec2").delete_transit_gateway_route` method.

Boto3 documentation:
[EC2.Client.delete_transit_gateway_route](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_transit_gateway_route)

Asynchronous method. Use `await delete_transit_gateway_route(...)` for a
synchronous call.

Arguments mapping described in
[DeleteTransitGatewayRouteRequestRequestTypeDef](./type_defs.md#deletetransitgatewayrouterequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayRouteTableId`: `str` *(required)*
- `DestinationCidrBlock`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteTransitGatewayRouteResultTypeDef](./type_defs.md#deletetransitgatewayrouteresulttypedef).

<a id="delete_transit_gateway_route_table"></a>

### delete_transit_gateway_route_table

Deletes the specified transit gateway route table.

Type annotations for
`aiobotocore.create_client("ec2").delete_transit_gateway_route_table` method.

Boto3 documentation:
[EC2.Client.delete_transit_gateway_route_table](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_transit_gateway_route_table)

Asynchronous method. Use `await delete_transit_gateway_route_table(...)` for a
synchronous call.

Arguments mapping described in
[DeleteTransitGatewayRouteTableRequestRequestTypeDef](./type_defs.md#deletetransitgatewayroutetablerequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayRouteTableId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteTransitGatewayRouteTableResultTypeDef](./type_defs.md#deletetransitgatewayroutetableresulttypedef).

<a id="delete_transit_gateway_vpc_attachment"></a>

### delete_transit_gateway_vpc_attachment

Deletes the specified VPC attachment.

Type annotations for
`aiobotocore.create_client("ec2").delete_transit_gateway_vpc_attachment`
method.

Boto3 documentation:
[EC2.Client.delete_transit_gateway_vpc_attachment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_transit_gateway_vpc_attachment)

Asynchronous method. Use `await delete_transit_gateway_vpc_attachment(...)` for
a synchronous call.

Arguments mapping described in
[DeleteTransitGatewayVpcAttachmentRequestRequestTypeDef](./type_defs.md#deletetransitgatewayvpcattachmentrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayAttachmentId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteTransitGatewayVpcAttachmentResultTypeDef](./type_defs.md#deletetransitgatewayvpcattachmentresulttypedef).

<a id="delete_volume"></a>

### delete_volume

Deletes the specified EBS volume.

Type annotations for `aiobotocore.create_client("ec2").delete_volume` method.

Boto3 documentation:
[EC2.Client.delete_volume](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_volume)

Asynchronous method. Use `await delete_volume(...)` for a synchronous call.

Arguments mapping described in
[DeleteVolumeRequestRequestTypeDef](./type_defs.md#deletevolumerequestrequesttypedef).

Keyword-only arguments:

- `VolumeId`: `str` *(required)*
- `DryRun`: `bool`

<a id="delete_vpc"></a>

### delete_vpc

Deletes the specified VPC.

Type annotations for `aiobotocore.create_client("ec2").delete_vpc` method.

Boto3 documentation:
[EC2.Client.delete_vpc](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_vpc)

Asynchronous method. Use `await delete_vpc(...)` for a synchronous call.

Arguments mapping described in
[DeleteVpcRequestRequestTypeDef](./type_defs.md#deletevpcrequestrequesttypedef).

Keyword-only arguments:

- `VpcId`: `str` *(required)*
- `DryRun`: `bool`

<a id="delete_vpc_endpoint_connection_notifications"></a>

### delete_vpc_endpoint_connection_notifications

Deletes one or more VPC endpoint connection notifications.

Type annotations for
`aiobotocore.create_client("ec2").delete_vpc_endpoint_connection_notifications`
method.

Boto3 documentation:
[EC2.Client.delete_vpc_endpoint_connection_notifications](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_vpc_endpoint_connection_notifications)

Asynchronous method. Use
`await delete_vpc_endpoint_connection_notifications(...)` for a synchronous
call.

Arguments mapping described in
[DeleteVpcEndpointConnectionNotificationsRequestRequestTypeDef](./type_defs.md#deletevpcendpointconnectionnotificationsrequestrequesttypedef).

Keyword-only arguments:

- `ConnectionNotificationIds`: `Sequence`\[`str`\] *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteVpcEndpointConnectionNotificationsResultTypeDef](./type_defs.md#deletevpcendpointconnectionnotificationsresulttypedef).

<a id="delete_vpc_endpoint_service_configurations"></a>

### delete_vpc_endpoint_service_configurations

Deletes one or more VPC endpoint service configurations in your account.

Type annotations for
`aiobotocore.create_client("ec2").delete_vpc_endpoint_service_configurations`
method.

Boto3 documentation:
[EC2.Client.delete_vpc_endpoint_service_configurations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_vpc_endpoint_service_configurations)

Asynchronous method. Use
`await delete_vpc_endpoint_service_configurations(...)` for a synchronous call.

Arguments mapping described in
[DeleteVpcEndpointServiceConfigurationsRequestRequestTypeDef](./type_defs.md#deletevpcendpointserviceconfigurationsrequestrequesttypedef).

Keyword-only arguments:

- `ServiceIds`: `Sequence`\[`str`\] *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteVpcEndpointServiceConfigurationsResultTypeDef](./type_defs.md#deletevpcendpointserviceconfigurationsresulttypedef).

<a id="delete_vpc_endpoints"></a>

### delete_vpc_endpoints

Deletes one or more specified VPC endpoints.

Type annotations for `aiobotocore.create_client("ec2").delete_vpc_endpoints`
method.

Boto3 documentation:
[EC2.Client.delete_vpc_endpoints](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_vpc_endpoints)

Asynchronous method. Use `await delete_vpc_endpoints(...)` for a synchronous
call.

Arguments mapping described in
[DeleteVpcEndpointsRequestRequestTypeDef](./type_defs.md#deletevpcendpointsrequestrequesttypedef).

Keyword-only arguments:

- `VpcEndpointIds`: `Sequence`\[`str`\] *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteVpcEndpointsResultTypeDef](./type_defs.md#deletevpcendpointsresulttypedef).

<a id="delete_vpc_peering_connection"></a>

### delete_vpc_peering_connection

Deletes a VPC peering connection.

Type annotations for
`aiobotocore.create_client("ec2").delete_vpc_peering_connection` method.

Boto3 documentation:
[EC2.Client.delete_vpc_peering_connection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_vpc_peering_connection)

Asynchronous method. Use `await delete_vpc_peering_connection(...)` for a
synchronous call.

Arguments mapping described in
[DeleteVpcPeeringConnectionRequestRequestTypeDef](./type_defs.md#deletevpcpeeringconnectionrequestrequesttypedef).

Keyword-only arguments:

- `VpcPeeringConnectionId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeleteVpcPeeringConnectionResultTypeDef](./type_defs.md#deletevpcpeeringconnectionresulttypedef).

<a id="delete_vpn_connection"></a>

### delete_vpn_connection

Deletes the specified VPN connection.

Type annotations for `aiobotocore.create_client("ec2").delete_vpn_connection`
method.

Boto3 documentation:
[EC2.Client.delete_vpn_connection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_vpn_connection)

Asynchronous method. Use `await delete_vpn_connection(...)` for a synchronous
call.

Arguments mapping described in
[DeleteVpnConnectionRequestRequestTypeDef](./type_defs.md#deletevpnconnectionrequestrequesttypedef).

Keyword-only arguments:

- `VpnConnectionId`: `str` *(required)*
- `DryRun`: `bool`

<a id="delete_vpn_connection_route"></a>

### delete_vpn_connection_route

Deletes the specified static route associated with a VPN connection between an
existing virtual private gateway and a VPN customer gateway.

Type annotations for
`aiobotocore.create_client("ec2").delete_vpn_connection_route` method.

Boto3 documentation:
[EC2.Client.delete_vpn_connection_route](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_vpn_connection_route)

Asynchronous method. Use `await delete_vpn_connection_route(...)` for a
synchronous call.

Arguments mapping described in
[DeleteVpnConnectionRouteRequestRequestTypeDef](./type_defs.md#deletevpnconnectionrouterequestrequesttypedef).

Keyword-only arguments:

- `DestinationCidrBlock`: `str` *(required)*
- `VpnConnectionId`: `str` *(required)*

<a id="delete_vpn_gateway"></a>

### delete_vpn_gateway

Deletes the specified virtual private gateway.

Type annotations for `aiobotocore.create_client("ec2").delete_vpn_gateway`
method.

Boto3 documentation:
[EC2.Client.delete_vpn_gateway](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.delete_vpn_gateway)

Asynchronous method. Use `await delete_vpn_gateway(...)` for a synchronous
call.

Arguments mapping described in
[DeleteVpnGatewayRequestRequestTypeDef](./type_defs.md#deletevpngatewayrequestrequesttypedef).

Keyword-only arguments:

- `VpnGatewayId`: `str` *(required)*
- `DryRun`: `bool`

<a id="deprovision_byoip_cidr"></a>

### deprovision_byoip_cidr

Releases the specified address range that you provisioned for use with your
Amazon Web Services resources through bring your own IP addresses (BYOIP) and
deletes the corresponding address pool.

Type annotations for `aiobotocore.create_client("ec2").deprovision_byoip_cidr`
method.

Boto3 documentation:
[EC2.Client.deprovision_byoip_cidr](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.deprovision_byoip_cidr)

Asynchronous method. Use `await deprovision_byoip_cidr(...)` for a synchronous
call.

Arguments mapping described in
[DeprovisionByoipCidrRequestRequestTypeDef](./type_defs.md#deprovisionbyoipcidrrequestrequesttypedef).

Keyword-only arguments:

- `Cidr`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeprovisionByoipCidrResultTypeDef](./type_defs.md#deprovisionbyoipcidrresulttypedef).

<a id="deprovision_ipam_pool_cidr"></a>

### deprovision_ipam_pool_cidr

Deprovision a CIDR provisioned from an IPAM pool.

Type annotations for
`aiobotocore.create_client("ec2").deprovision_ipam_pool_cidr` method.

Boto3 documentation:
[EC2.Client.deprovision_ipam_pool_cidr](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.deprovision_ipam_pool_cidr)

Asynchronous method. Use `await deprovision_ipam_pool_cidr(...)` for a
synchronous call.

Arguments mapping described in
[DeprovisionIpamPoolCidrRequestRequestTypeDef](./type_defs.md#deprovisionipampoolcidrrequestrequesttypedef).

Keyword-only arguments:

- `IpamPoolId`: `str` *(required)*
- `DryRun`: `bool`
- `Cidr`: `str`

Returns a `Coroutine` for
[DeprovisionIpamPoolCidrResultTypeDef](./type_defs.md#deprovisionipampoolcidrresulttypedef).

<a id="deprovision_public_ipv4_pool_cidr"></a>

### deprovision_public_ipv4_pool_cidr

Deprovision a CIDR from a public IPv4 pool.

Type annotations for
`aiobotocore.create_client("ec2").deprovision_public_ipv4_pool_cidr` method.

Boto3 documentation:
[EC2.Client.deprovision_public_ipv4_pool_cidr](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.deprovision_public_ipv4_pool_cidr)

Asynchronous method. Use `await deprovision_public_ipv4_pool_cidr(...)` for a
synchronous call.

Arguments mapping described in
[DeprovisionPublicIpv4PoolCidrRequestRequestTypeDef](./type_defs.md#deprovisionpublicipv4poolcidrrequestrequesttypedef).

Keyword-only arguments:

- `PoolId`: `str` *(required)*
- `Cidr`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeprovisionPublicIpv4PoolCidrResultTypeDef](./type_defs.md#deprovisionpublicipv4poolcidrresulttypedef).

<a id="deregister_image"></a>

### deregister_image

Deregisters the specified AMI.

Type annotations for `aiobotocore.create_client("ec2").deregister_image`
method.

Boto3 documentation:
[EC2.Client.deregister_image](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.deregister_image)

Asynchronous method. Use `await deregister_image(...)` for a synchronous call.

Arguments mapping described in
[DeregisterImageRequestRequestTypeDef](./type_defs.md#deregisterimagerequestrequesttypedef).

Keyword-only arguments:

- `ImageId`: `str` *(required)*
- `DryRun`: `bool`

<a id="deregister_instance_event_notification_attributes"></a>

### deregister_instance_event_notification_attributes

c Deregisters tag keys to prevent tags that have the specified tag keys from
being included in scheduled event notifications for resources in the Region.

Type annotations for
`aiobotocore.create_client("ec2").deregister_instance_event_notification_attributes`
method.

Boto3 documentation:
[EC2.Client.deregister_instance_event_notification_attributes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.deregister_instance_event_notification_attributes)

Asynchronous method. Use
`await deregister_instance_event_notification_attributes(...)` for a
synchronous call.

Arguments mapping described in
[DeregisterInstanceEventNotificationAttributesRequestRequestTypeDef](./type_defs.md#deregisterinstanceeventnotificationattributesrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `InstanceTagAttribute`:
  [DeregisterInstanceTagAttributeRequestTypeDef](./type_defs.md#deregisterinstancetagattributerequesttypedef)

Returns a `Coroutine` for
[DeregisterInstanceEventNotificationAttributesResultTypeDef](./type_defs.md#deregisterinstanceeventnotificationattributesresulttypedef).

<a id="deregister_transit_gateway_multicast_group_members"></a>

### deregister_transit_gateway_multicast_group_members

Deregisters the specified members (network interfaces) from the transit gateway
multicast group.

Type annotations for
`aiobotocore.create_client("ec2").deregister_transit_gateway_multicast_group_members`
method.

Boto3 documentation:
[EC2.Client.deregister_transit_gateway_multicast_group_members](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.deregister_transit_gateway_multicast_group_members)

Asynchronous method. Use
`await deregister_transit_gateway_multicast_group_members(...)` for a
synchronous call.

Arguments mapping described in
[DeregisterTransitGatewayMulticastGroupMembersRequestRequestTypeDef](./type_defs.md#deregistertransitgatewaymulticastgroupmembersrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayMulticastDomainId`: `str`
- `GroupIpAddress`: `str`
- `NetworkInterfaceIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeregisterTransitGatewayMulticastGroupMembersResultTypeDef](./type_defs.md#deregistertransitgatewaymulticastgroupmembersresulttypedef).

<a id="deregister_transit_gateway_multicast_group_sources"></a>

### deregister_transit_gateway_multicast_group_sources

Deregisters the specified sources (network interfaces) from the transit gateway
multicast group.

Type annotations for
`aiobotocore.create_client("ec2").deregister_transit_gateway_multicast_group_sources`
method.

Boto3 documentation:
[EC2.Client.deregister_transit_gateway_multicast_group_sources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.deregister_transit_gateway_multicast_group_sources)

Asynchronous method. Use
`await deregister_transit_gateway_multicast_group_sources(...)` for a
synchronous call.

Arguments mapping described in
[DeregisterTransitGatewayMulticastGroupSourcesRequestRequestTypeDef](./type_defs.md#deregistertransitgatewaymulticastgroupsourcesrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayMulticastDomainId`: `str`
- `GroupIpAddress`: `str`
- `NetworkInterfaceIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[DeregisterTransitGatewayMulticastGroupSourcesResultTypeDef](./type_defs.md#deregistertransitgatewaymulticastgroupsourcesresulttypedef).

<a id="describe_account_attributes"></a>

### describe_account_attributes

Describes attributes of your AWS account.

Type annotations for
`aiobotocore.create_client("ec2").describe_account_attributes` method.

Boto3 documentation:
[EC2.Client.describe_account_attributes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_account_attributes)

Asynchronous method. Use `await describe_account_attributes(...)` for a
synchronous call.

Arguments mapping described in
[DescribeAccountAttributesRequestRequestTypeDef](./type_defs.md#describeaccountattributesrequestrequesttypedef).

Keyword-only arguments:

- `AttributeNames`:
  `Sequence`\[[AccountAttributeNameType](./literals.md#accountattributenametype)\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeAccountAttributesResultTypeDef](./type_defs.md#describeaccountattributesresulttypedef).

<a id="describe_addresses"></a>

### describe_addresses

Describes the specified Elastic IP addresses or all of your Elastic IP
addresses.

Type annotations for `aiobotocore.create_client("ec2").describe_addresses`
method.

Boto3 documentation:
[EC2.Client.describe_addresses](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_addresses)

Asynchronous method. Use `await describe_addresses(...)` for a synchronous
call.

Arguments mapping described in
[DescribeAddressesRequestRequestTypeDef](./type_defs.md#describeaddressesrequestrequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `PublicIps`: `Sequence`\[`str`\]
- `AllocationIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeAddressesResultTypeDef](./type_defs.md#describeaddressesresulttypedef).

<a id="describe_addresses_attribute"></a>

### describe_addresses_attribute

Describes the attributes of the specified Elastic IP addresses.

Type annotations for
`aiobotocore.create_client("ec2").describe_addresses_attribute` method.

Boto3 documentation:
[EC2.Client.describe_addresses_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_addresses_attribute)

Asynchronous method. Use `await describe_addresses_attribute(...)` for a
synchronous call.

Arguments mapping described in
[DescribeAddressesAttributeRequestRequestTypeDef](./type_defs.md#describeaddressesattributerequestrequesttypedef).

Keyword-only arguments:

- `AllocationIds`: `Sequence`\[`str`\]
- `Attribute`: `Literal['domain-name']` (see
  [AddressAttributeNameType](./literals.md#addressattributenametype))
- `NextToken`: `str`
- `MaxResults`: `int`
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeAddressesAttributeResultTypeDef](./type_defs.md#describeaddressesattributeresulttypedef).

<a id="describe_aggregate_id_format"></a>

### describe_aggregate_id_format

Describes the longer ID format settings for all resource types in a specific
Region.

Type annotations for
`aiobotocore.create_client("ec2").describe_aggregate_id_format` method.

Boto3 documentation:
[EC2.Client.describe_aggregate_id_format](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_aggregate_id_format)

Asynchronous method. Use `await describe_aggregate_id_format(...)` for a
synchronous call.

Arguments mapping described in
[DescribeAggregateIdFormatRequestRequestTypeDef](./type_defs.md#describeaggregateidformatrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeAggregateIdFormatResultTypeDef](./type_defs.md#describeaggregateidformatresulttypedef).

<a id="describe_availability_zones"></a>

### describe_availability_zones

Describes the Availability Zones, Local Zones, and Wavelength Zones that are
available to you.

Type annotations for
`aiobotocore.create_client("ec2").describe_availability_zones` method.

Boto3 documentation:
[EC2.Client.describe_availability_zones](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_availability_zones)

Asynchronous method. Use `await describe_availability_zones(...)` for a
synchronous call.

Arguments mapping described in
[DescribeAvailabilityZonesRequestRequestTypeDef](./type_defs.md#describeavailabilityzonesrequestrequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `ZoneNames`: `Sequence`\[`str`\]
- `ZoneIds`: `Sequence`\[`str`\]
- `AllAvailabilityZones`: `bool`
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeAvailabilityZonesResultTypeDef](./type_defs.md#describeavailabilityzonesresulttypedef).

<a id="describe_bundle_tasks"></a>

### describe_bundle_tasks

Describes the specified bundle tasks or all of your bundle tasks.

Type annotations for `aiobotocore.create_client("ec2").describe_bundle_tasks`
method.

Boto3 documentation:
[EC2.Client.describe_bundle_tasks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_bundle_tasks)

Asynchronous method. Use `await describe_bundle_tasks(...)` for a synchronous
call.

Arguments mapping described in
[DescribeBundleTasksRequestRequestTypeDef](./type_defs.md#describebundletasksrequestrequesttypedef).

Keyword-only arguments:

- `BundleIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeBundleTasksResultTypeDef](./type_defs.md#describebundletasksresulttypedef).

<a id="describe_byoip_cidrs"></a>

### describe_byoip_cidrs

Describes the IP address ranges that were specified in calls to
ProvisionByoipCidr .

Type annotations for `aiobotocore.create_client("ec2").describe_byoip_cidrs`
method.

Boto3 documentation:
[EC2.Client.describe_byoip_cidrs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_byoip_cidrs)

Asynchronous method. Use `await describe_byoip_cidrs(...)` for a synchronous
call.

Arguments mapping described in
[DescribeByoipCidrsRequestRequestTypeDef](./type_defs.md#describebyoipcidrsrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int` *(required)*
- `DryRun`: `bool`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeByoipCidrsResultTypeDef](./type_defs.md#describebyoipcidrsresulttypedef).

<a id="describe_capacity_reservation_fleets"></a>

### describe_capacity_reservation_fleets

Describes one or more Capacity Reservation Fleets.

Type annotations for
`aiobotocore.create_client("ec2").describe_capacity_reservation_fleets` method.

Boto3 documentation:
[EC2.Client.describe_capacity_reservation_fleets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_capacity_reservation_fleets)

Asynchronous method. Use `await describe_capacity_reservation_fleets(...)` for
a synchronous call.

Arguments mapping described in
[DescribeCapacityReservationFleetsRequestRequestTypeDef](./type_defs.md#describecapacityreservationfleetsrequestrequesttypedef).

Keyword-only arguments:

- `CapacityReservationFleetIds`: `Sequence`\[`str`\]
- `NextToken`: `str`
- `MaxResults`: `int`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeCapacityReservationFleetsResultTypeDef](./type_defs.md#describecapacityreservationfleetsresulttypedef).

<a id="describe_capacity_reservations"></a>

### describe_capacity_reservations

Describes one or more of your Capacity Reservations.

Type annotations for
`aiobotocore.create_client("ec2").describe_capacity_reservations` method.

Boto3 documentation:
[EC2.Client.describe_capacity_reservations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_capacity_reservations)

Asynchronous method. Use `await describe_capacity_reservations(...)` for a
synchronous call.

Arguments mapping described in
[DescribeCapacityReservationsRequestRequestTypeDef](./type_defs.md#describecapacityreservationsrequestrequesttypedef).

Keyword-only arguments:

- `CapacityReservationIds`: `Sequence`\[`str`\]
- `NextToken`: `str`
- `MaxResults`: `int`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeCapacityReservationsResultTypeDef](./type_defs.md#describecapacityreservationsresulttypedef).

<a id="describe_carrier_gateways"></a>

### describe_carrier_gateways

Describes one or more of your carrier gateways.

Type annotations for
`aiobotocore.create_client("ec2").describe_carrier_gateways` method.

Boto3 documentation:
[EC2.Client.describe_carrier_gateways](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_carrier_gateways)

Asynchronous method. Use `await describe_carrier_gateways(...)` for a
synchronous call.

Arguments mapping described in
[DescribeCarrierGatewaysRequestRequestTypeDef](./type_defs.md#describecarriergatewaysrequestrequesttypedef).

Keyword-only arguments:

- `CarrierGatewayIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeCarrierGatewaysResultTypeDef](./type_defs.md#describecarriergatewaysresulttypedef).

<a id="describe_classic_link_instances"></a>

### describe_classic_link_instances

Describes one or more of your linked EC2-Classic instances.

Type annotations for
`aiobotocore.create_client("ec2").describe_classic_link_instances` method.

Boto3 documentation:
[EC2.Client.describe_classic_link_instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_classic_link_instances)

Asynchronous method. Use `await describe_classic_link_instances(...)` for a
synchronous call.

Arguments mapping described in
[DescribeClassicLinkInstancesRequestRequestTypeDef](./type_defs.md#describeclassiclinkinstancesrequestrequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `InstanceIds`: `Sequence`\[`str`\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeClassicLinkInstancesResultTypeDef](./type_defs.md#describeclassiclinkinstancesresulttypedef).

<a id="describe_client_vpn_authorization_rules"></a>

### describe_client_vpn_authorization_rules

Describes the authorization rules for a specified Client VPN endpoint.

Type annotations for
`aiobotocore.create_client("ec2").describe_client_vpn_authorization_rules`
method.

Boto3 documentation:
[EC2.Client.describe_client_vpn_authorization_rules](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_client_vpn_authorization_rules)

Asynchronous method. Use `await describe_client_vpn_authorization_rules(...)`
for a synchronous call.

Arguments mapping described in
[DescribeClientVpnAuthorizationRulesRequestRequestTypeDef](./type_defs.md#describeclientvpnauthorizationrulesrequestrequesttypedef).

Keyword-only arguments:

- `ClientVpnEndpointId`: `str` *(required)*
- `DryRun`: `bool`
- `NextToken`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`

Returns a `Coroutine` for
[DescribeClientVpnAuthorizationRulesResultTypeDef](./type_defs.md#describeclientvpnauthorizationrulesresulttypedef).

<a id="describe_client_vpn_connections"></a>

### describe_client_vpn_connections

Describes active client connections and connections that have been terminated
within the last 60 minutes for the specified Client VPN endpoint.

Type annotations for
`aiobotocore.create_client("ec2").describe_client_vpn_connections` method.

Boto3 documentation:
[EC2.Client.describe_client_vpn_connections](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_client_vpn_connections)

Asynchronous method. Use `await describe_client_vpn_connections(...)` for a
synchronous call.

Arguments mapping described in
[DescribeClientVpnConnectionsRequestRequestTypeDef](./type_defs.md#describeclientvpnconnectionsrequestrequesttypedef).

Keyword-only arguments:

- `ClientVpnEndpointId`: `str` *(required)*
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `NextToken`: `str`
- `MaxResults`: `int`
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeClientVpnConnectionsResultTypeDef](./type_defs.md#describeclientvpnconnectionsresulttypedef).

<a id="describe_client_vpn_endpoints"></a>

### describe_client_vpn_endpoints

Describes one or more Client VPN endpoints in the account.

Type annotations for
`aiobotocore.create_client("ec2").describe_client_vpn_endpoints` method.

Boto3 documentation:
[EC2.Client.describe_client_vpn_endpoints](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_client_vpn_endpoints)

Asynchronous method. Use `await describe_client_vpn_endpoints(...)` for a
synchronous call.

Arguments mapping described in
[DescribeClientVpnEndpointsRequestRequestTypeDef](./type_defs.md#describeclientvpnendpointsrequestrequesttypedef).

Keyword-only arguments:

- `ClientVpnEndpointIds`: `Sequence`\[`str`\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeClientVpnEndpointsResultTypeDef](./type_defs.md#describeclientvpnendpointsresulttypedef).

<a id="describe_client_vpn_routes"></a>

### describe_client_vpn_routes

Describes the routes for the specified Client VPN endpoint.

Type annotations for
`aiobotocore.create_client("ec2").describe_client_vpn_routes` method.

Boto3 documentation:
[EC2.Client.describe_client_vpn_routes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_client_vpn_routes)

Asynchronous method. Use `await describe_client_vpn_routes(...)` for a
synchronous call.

Arguments mapping described in
[DescribeClientVpnRoutesRequestRequestTypeDef](./type_defs.md#describeclientvpnroutesrequestrequesttypedef).

Keyword-only arguments:

- `ClientVpnEndpointId`: `str` *(required)*
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeClientVpnRoutesResultTypeDef](./type_defs.md#describeclientvpnroutesresulttypedef).

<a id="describe_client_vpn_target_networks"></a>

### describe_client_vpn_target_networks

Describes the target networks associated with the specified Client VPN
endpoint.

Type annotations for
`aiobotocore.create_client("ec2").describe_client_vpn_target_networks` method.

Boto3 documentation:
[EC2.Client.describe_client_vpn_target_networks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_client_vpn_target_networks)

Asynchronous method. Use `await describe_client_vpn_target_networks(...)` for a
synchronous call.

Arguments mapping described in
[DescribeClientVpnTargetNetworksRequestRequestTypeDef](./type_defs.md#describeclientvpntargetnetworksrequestrequesttypedef).

Keyword-only arguments:

- `ClientVpnEndpointId`: `str` *(required)*
- `AssociationIds`: `Sequence`\[`str`\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeClientVpnTargetNetworksResultTypeDef](./type_defs.md#describeclientvpntargetnetworksresulttypedef).

<a id="describe_coip_pools"></a>

### describe_coip_pools

Describes the specified customer-owned address pools or all of your customer-
owned address pools.

Type annotations for `aiobotocore.create_client("ec2").describe_coip_pools`
method.

Boto3 documentation:
[EC2.Client.describe_coip_pools](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_coip_pools)

Asynchronous method. Use `await describe_coip_pools(...)` for a synchronous
call.

Arguments mapping described in
[DescribeCoipPoolsRequestRequestTypeDef](./type_defs.md#describecoippoolsrequestrequesttypedef).

Keyword-only arguments:

- `PoolIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeCoipPoolsResultTypeDef](./type_defs.md#describecoippoolsresulttypedef).

<a id="describe_conversion_tasks"></a>

### describe_conversion_tasks

Describes the specified conversion tasks or all your conversion tasks.

Type annotations for
`aiobotocore.create_client("ec2").describe_conversion_tasks` method.

Boto3 documentation:
[EC2.Client.describe_conversion_tasks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_conversion_tasks)

Asynchronous method. Use `await describe_conversion_tasks(...)` for a
synchronous call.

Arguments mapping described in
[DescribeConversionTasksRequestRequestTypeDef](./type_defs.md#describeconversiontasksrequestrequesttypedef).

Keyword-only arguments:

- `ConversionTaskIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeConversionTasksResultTypeDef](./type_defs.md#describeconversiontasksresulttypedef).

<a id="describe_customer_gateways"></a>

### describe_customer_gateways

Describes one or more of your VPN customer gateways.

Type annotations for
`aiobotocore.create_client("ec2").describe_customer_gateways` method.

Boto3 documentation:
[EC2.Client.describe_customer_gateways](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_customer_gateways)

Asynchronous method. Use `await describe_customer_gateways(...)` for a
synchronous call.

Arguments mapping described in
[DescribeCustomerGatewaysRequestRequestTypeDef](./type_defs.md#describecustomergatewaysrequestrequesttypedef).

Keyword-only arguments:

- `CustomerGatewayIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeCustomerGatewaysResultTypeDef](./type_defs.md#describecustomergatewaysresulttypedef).

<a id="describe_dhcp_options"></a>

### describe_dhcp_options

Describes one or more of your DHCP options sets.

Type annotations for `aiobotocore.create_client("ec2").describe_dhcp_options`
method.

Boto3 documentation:
[EC2.Client.describe_dhcp_options](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_dhcp_options)

Asynchronous method. Use `await describe_dhcp_options(...)` for a synchronous
call.

Arguments mapping described in
[DescribeDhcpOptionsRequestRequestTypeDef](./type_defs.md#describedhcpoptionsrequestrequesttypedef).

Keyword-only arguments:

- `DhcpOptionsIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[DescribeDhcpOptionsResultTypeDef](./type_defs.md#describedhcpoptionsresulttypedef).

<a id="describe_egress_only_internet_gateways"></a>

### describe_egress_only_internet_gateways

Describes one or more of your egress-only internet gateways.

Type annotations for
`aiobotocore.create_client("ec2").describe_egress_only_internet_gateways`
method.

Boto3 documentation:
[EC2.Client.describe_egress_only_internet_gateways](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_egress_only_internet_gateways)

Asynchronous method. Use `await describe_egress_only_internet_gateways(...)`
for a synchronous call.

Arguments mapping described in
[DescribeEgressOnlyInternetGatewaysRequestRequestTypeDef](./type_defs.md#describeegressonlyinternetgatewaysrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `EgressOnlyInternetGatewayIds`: `Sequence`\[`str`\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]

Returns a `Coroutine` for
[DescribeEgressOnlyInternetGatewaysResultTypeDef](./type_defs.md#describeegressonlyinternetgatewaysresulttypedef).

<a id="describe_elastic_gpus"></a>

### describe_elastic_gpus

Describes the Elastic Graphics accelerator associated with your instances.

Type annotations for `aiobotocore.create_client("ec2").describe_elastic_gpus`
method.

Boto3 documentation:
[EC2.Client.describe_elastic_gpus](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_elastic_gpus)

Asynchronous method. Use `await describe_elastic_gpus(...)` for a synchronous
call.

Arguments mapping described in
[DescribeElasticGpusRequestRequestTypeDef](./type_defs.md#describeelasticgpusrequestrequesttypedef).

Keyword-only arguments:

- `ElasticGpuIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeElasticGpusResultTypeDef](./type_defs.md#describeelasticgpusresulttypedef).

<a id="describe_export_image_tasks"></a>

### describe_export_image_tasks

Describes the specified export image tasks or all of your export image tasks.

Type annotations for
`aiobotocore.create_client("ec2").describe_export_image_tasks` method.

Boto3 documentation:
[EC2.Client.describe_export_image_tasks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_export_image_tasks)

Asynchronous method. Use `await describe_export_image_tasks(...)` for a
synchronous call.

Arguments mapping described in
[DescribeExportImageTasksRequestRequestTypeDef](./type_defs.md#describeexportimagetasksrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `ExportImageTaskIds`: `Sequence`\[`str`\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeExportImageTasksResultTypeDef](./type_defs.md#describeexportimagetasksresulttypedef).

<a id="describe_export_tasks"></a>

### describe_export_tasks

Describes the specified export instance tasks or all of your export instance
tasks.

Type annotations for `aiobotocore.create_client("ec2").describe_export_tasks`
method.

Boto3 documentation:
[EC2.Client.describe_export_tasks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_export_tasks)

Asynchronous method. Use `await describe_export_tasks(...)` for a synchronous
call.

Arguments mapping described in
[DescribeExportTasksRequestRequestTypeDef](./type_defs.md#describeexporttasksrequestrequesttypedef).

Keyword-only arguments:

- `ExportTaskIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]

Returns a `Coroutine` for
[DescribeExportTasksResultTypeDef](./type_defs.md#describeexporttasksresulttypedef).

<a id="describe_fast_snapshot_restores"></a>

### describe_fast_snapshot_restores

Describes the state of fast snapshot restores for your snapshots.

Type annotations for
`aiobotocore.create_client("ec2").describe_fast_snapshot_restores` method.

Boto3 documentation:
[EC2.Client.describe_fast_snapshot_restores](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_fast_snapshot_restores)

Asynchronous method. Use `await describe_fast_snapshot_restores(...)` for a
synchronous call.

Arguments mapping described in
[DescribeFastSnapshotRestoresRequestRequestTypeDef](./type_defs.md#describefastsnapshotrestoresrequestrequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeFastSnapshotRestoresResultTypeDef](./type_defs.md#describefastsnapshotrestoresresulttypedef).

<a id="describe_fleet_history"></a>

### describe_fleet_history

Describes the events for the specified EC2 Fleet during the specified time.

Type annotations for `aiobotocore.create_client("ec2").describe_fleet_history`
method.

Boto3 documentation:
[EC2.Client.describe_fleet_history](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_fleet_history)

Asynchronous method. Use `await describe_fleet_history(...)` for a synchronous
call.

Arguments mapping described in
[DescribeFleetHistoryRequestRequestTypeDef](./type_defs.md#describefleethistoryrequestrequesttypedef).

Keyword-only arguments:

- `FleetId`: `str` *(required)*
- `StartTime`: `Union`\[`datetime`, `str`\] *(required)*
- `DryRun`: `bool`
- `EventType`: [FleetEventTypeType](./literals.md#fleeteventtypetype)
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeFleetHistoryResultTypeDef](./type_defs.md#describefleethistoryresulttypedef).

<a id="describe_fleet_instances"></a>

### describe_fleet_instances

Describes the running instances for the specified EC2 Fleet.

Type annotations for
`aiobotocore.create_client("ec2").describe_fleet_instances` method.

Boto3 documentation:
[EC2.Client.describe_fleet_instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_fleet_instances)

Asynchronous method. Use `await describe_fleet_instances(...)` for a
synchronous call.

Arguments mapping described in
[DescribeFleetInstancesRequestRequestTypeDef](./type_defs.md#describefleetinstancesrequestrequesttypedef).

Keyword-only arguments:

- `FleetId`: `str` *(required)*
- `DryRun`: `bool`
- `MaxResults`: `int`
- `NextToken`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]

Returns a `Coroutine` for
[DescribeFleetInstancesResultTypeDef](./type_defs.md#describefleetinstancesresulttypedef).

<a id="describe_fleets"></a>

### describe_fleets

Describes the specified EC2 Fleets or all of your EC2 Fleets.

Type annotations for `aiobotocore.create_client("ec2").describe_fleets` method.

Boto3 documentation:
[EC2.Client.describe_fleets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_fleets)

Asynchronous method. Use `await describe_fleets(...)` for a synchronous call.

Arguments mapping described in
[DescribeFleetsRequestRequestTypeDef](./type_defs.md#describefleetsrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `MaxResults`: `int`
- `NextToken`: `str`
- `FleetIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]

Returns a `Coroutine` for
[DescribeFleetsResultTypeDef](./type_defs.md#describefleetsresulttypedef).

<a id="describe_flow_logs"></a>

### describe_flow_logs

Describes one or more flow logs.

Type annotations for `aiobotocore.create_client("ec2").describe_flow_logs`
method.

Boto3 documentation:
[EC2.Client.describe_flow_logs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_flow_logs)

Asynchronous method. Use `await describe_flow_logs(...)` for a synchronous
call.

Arguments mapping described in
[DescribeFlowLogsRequestRequestTypeDef](./type_defs.md#describeflowlogsrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `FlowLogIds`: `Sequence`\[`str`\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeFlowLogsResultTypeDef](./type_defs.md#describeflowlogsresulttypedef).

<a id="describe_fpga_image_attribute"></a>

### describe_fpga_image_attribute

Describes the specified attribute of the specified Amazon FPGA Image (AFI).

Type annotations for
`aiobotocore.create_client("ec2").describe_fpga_image_attribute` method.

Boto3 documentation:
[EC2.Client.describe_fpga_image_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_fpga_image_attribute)

Asynchronous method. Use `await describe_fpga_image_attribute(...)` for a
synchronous call.

Arguments mapping described in
[DescribeFpgaImageAttributeRequestRequestTypeDef](./type_defs.md#describefpgaimageattributerequestrequesttypedef).

Keyword-only arguments:

- `FpgaImageId`: `str` *(required)*
- `Attribute`:
  [FpgaImageAttributeNameType](./literals.md#fpgaimageattributenametype)
  *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeFpgaImageAttributeResultTypeDef](./type_defs.md#describefpgaimageattributeresulttypedef).

<a id="describe_fpga_images"></a>

### describe_fpga_images

Describes the Amazon FPGA Images (AFIs) available to you.

Type annotations for `aiobotocore.create_client("ec2").describe_fpga_images`
method.

Boto3 documentation:
[EC2.Client.describe_fpga_images](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_fpga_images)

Asynchronous method. Use `await describe_fpga_images(...)` for a synchronous
call.

Arguments mapping described in
[DescribeFpgaImagesRequestRequestTypeDef](./type_defs.md#describefpgaimagesrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `FpgaImageIds`: `Sequence`\[`str`\]
- `Owners`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[DescribeFpgaImagesResultTypeDef](./type_defs.md#describefpgaimagesresulttypedef).

<a id="describe_host_reservation_offerings"></a>

### describe_host_reservation_offerings

Describes the Dedicated Host reservations that are available to purchase.

Type annotations for
`aiobotocore.create_client("ec2").describe_host_reservation_offerings` method.

Boto3 documentation:
[EC2.Client.describe_host_reservation_offerings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_host_reservation_offerings)

Asynchronous method. Use `await describe_host_reservation_offerings(...)` for a
synchronous call.

Arguments mapping described in
[DescribeHostReservationOfferingsRequestRequestTypeDef](./type_defs.md#describehostreservationofferingsrequestrequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxDuration`: `int`
- `MaxResults`: `int`
- `MinDuration`: `int`
- `NextToken`: `str`
- `OfferingId`: `str`

Returns a `Coroutine` for
[DescribeHostReservationOfferingsResultTypeDef](./type_defs.md#describehostreservationofferingsresulttypedef).

<a id="describe_host_reservations"></a>

### describe_host_reservations

Describes reservations that are associated with Dedicated Hosts in your
account.

Type annotations for
`aiobotocore.create_client("ec2").describe_host_reservations` method.

Boto3 documentation:
[EC2.Client.describe_host_reservations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_host_reservations)

Asynchronous method. Use `await describe_host_reservations(...)` for a
synchronous call.

Arguments mapping described in
[DescribeHostReservationsRequestRequestTypeDef](./type_defs.md#describehostreservationsrequestrequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `HostReservationIdSet`: `Sequence`\[`str`\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeHostReservationsResultTypeDef](./type_defs.md#describehostreservationsresulttypedef).

<a id="describe_hosts"></a>

### describe_hosts

Describes the specified Dedicated Hosts or all your Dedicated Hosts.

Type annotations for `aiobotocore.create_client("ec2").describe_hosts` method.

Boto3 documentation:
[EC2.Client.describe_hosts](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_hosts)

Asynchronous method. Use `await describe_hosts(...)` for a synchronous call.

Arguments mapping described in
[DescribeHostsRequestRequestTypeDef](./type_defs.md#describehostsrequestrequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `HostIds`: `Sequence`\[`str`\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeHostsResultTypeDef](./type_defs.md#describehostsresulttypedef).

<a id="describe_iam_instance_profile_associations"></a>

### describe_iam_instance_profile_associations

Describes your IAM instance profile associations.

Type annotations for
`aiobotocore.create_client("ec2").describe_iam_instance_profile_associations`
method.

Boto3 documentation:
[EC2.Client.describe_iam_instance_profile_associations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_iam_instance_profile_associations)

Asynchronous method. Use
`await describe_iam_instance_profile_associations(...)` for a synchronous call.

Arguments mapping described in
[DescribeIamInstanceProfileAssociationsRequestRequestTypeDef](./type_defs.md#describeiaminstanceprofileassociationsrequestrequesttypedef).

Keyword-only arguments:

- `AssociationIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeIamInstanceProfileAssociationsResultTypeDef](./type_defs.md#describeiaminstanceprofileassociationsresulttypedef).

<a id="describe_id_format"></a>

### describe_id_format

Describes the ID format settings for your resources on a per-Region basis, for
example, to view which resource types are enabled for longer IDs.

Type annotations for `aiobotocore.create_client("ec2").describe_id_format`
method.

Boto3 documentation:
[EC2.Client.describe_id_format](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_id_format)

Asynchronous method. Use `await describe_id_format(...)` for a synchronous
call.

Arguments mapping described in
[DescribeIdFormatRequestRequestTypeDef](./type_defs.md#describeidformatrequestrequesttypedef).

Keyword-only arguments:

- `Resource`: `str`

Returns a `Coroutine` for
[DescribeIdFormatResultTypeDef](./type_defs.md#describeidformatresulttypedef).

<a id="describe_identity_id_format"></a>

### describe_identity_id_format

Describes the ID format settings for resources for the specified IAM user, IAM
role, or root user.

Type annotations for
`aiobotocore.create_client("ec2").describe_identity_id_format` method.

Boto3 documentation:
[EC2.Client.describe_identity_id_format](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_identity_id_format)

Asynchronous method. Use `await describe_identity_id_format(...)` for a
synchronous call.

Arguments mapping described in
[DescribeIdentityIdFormatRequestRequestTypeDef](./type_defs.md#describeidentityidformatrequestrequesttypedef).

Keyword-only arguments:

- `PrincipalArn`: `str` *(required)*
- `Resource`: `str`

Returns a `Coroutine` for
[DescribeIdentityIdFormatResultTypeDef](./type_defs.md#describeidentityidformatresulttypedef).

<a id="describe_image_attribute"></a>

### describe_image_attribute

Describes the specified attribute of the specified AMI.

Type annotations for
`aiobotocore.create_client("ec2").describe_image_attribute` method.

Boto3 documentation:
[EC2.Client.describe_image_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_image_attribute)

Asynchronous method. Use `await describe_image_attribute(...)` for a
synchronous call.

Arguments mapping described in
[DescribeImageAttributeRequestRequestTypeDef](./type_defs.md#describeimageattributerequestrequesttypedef).

Keyword-only arguments:

- `Attribute`: [ImageAttributeNameType](./literals.md#imageattributenametype)
  *(required)*
- `ImageId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[ImageAttributeTypeDef](./type_defs.md#imageattributetypedef).

<a id="describe_images"></a>

### describe_images

Describes the specified images (AMIs, AKIs, and ARIs) available to you or all
of the images available to you.

Type annotations for `aiobotocore.create_client("ec2").describe_images` method.

Boto3 documentation:
[EC2.Client.describe_images](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_images)

Asynchronous method. Use `await describe_images(...)` for a synchronous call.

Arguments mapping described in
[DescribeImagesRequestRequestTypeDef](./type_defs.md#describeimagesrequestrequesttypedef).

Keyword-only arguments:

- `ExecutableUsers`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `ImageIds`: `Sequence`\[`str`\]
- `Owners`: `Sequence`\[`str`\]
- `IncludeDeprecated`: `bool`
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeImagesResultTypeDef](./type_defs.md#describeimagesresulttypedef).

<a id="describe_import_image_tasks"></a>

### describe_import_image_tasks

Displays details about an import virtual machine or import snapshot tasks that
are already created.

Type annotations for
`aiobotocore.create_client("ec2").describe_import_image_tasks` method.

Boto3 documentation:
[EC2.Client.describe_import_image_tasks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_import_image_tasks)

Asynchronous method. Use `await describe_import_image_tasks(...)` for a
synchronous call.

Arguments mapping described in
[DescribeImportImageTasksRequestRequestTypeDef](./type_defs.md#describeimportimagetasksrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `ImportTaskIds`: `Sequence`\[`str`\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeImportImageTasksResultTypeDef](./type_defs.md#describeimportimagetasksresulttypedef).

<a id="describe_import_snapshot_tasks"></a>

### describe_import_snapshot_tasks

Describes your import snapshot tasks.

Type annotations for
`aiobotocore.create_client("ec2").describe_import_snapshot_tasks` method.

Boto3 documentation:
[EC2.Client.describe_import_snapshot_tasks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_import_snapshot_tasks)

Asynchronous method. Use `await describe_import_snapshot_tasks(...)` for a
synchronous call.

Arguments mapping described in
[DescribeImportSnapshotTasksRequestRequestTypeDef](./type_defs.md#describeimportsnapshottasksrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `ImportTaskIds`: `Sequence`\[`str`\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeImportSnapshotTasksResultTypeDef](./type_defs.md#describeimportsnapshottasksresulttypedef).

<a id="describe_instance_attribute"></a>

### describe_instance_attribute

Describes the specified attribute of the specified instance.

Type annotations for
`aiobotocore.create_client("ec2").describe_instance_attribute` method.

Boto3 documentation:
[EC2.Client.describe_instance_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_instance_attribute)

Asynchronous method. Use `await describe_instance_attribute(...)` for a
synchronous call.

Arguments mapping described in
[DescribeInstanceAttributeRequestRequestTypeDef](./type_defs.md#describeinstanceattributerequestrequesttypedef).

Keyword-only arguments:

- `Attribute`:
  [InstanceAttributeNameType](./literals.md#instanceattributenametype)
  *(required)*
- `InstanceId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[InstanceAttributeTypeDef](./type_defs.md#instanceattributetypedef).

<a id="describe_instance_credit_specifications"></a>

### describe_instance_credit_specifications

Describes the credit option for CPU usage of the specified burstable
performance instances.

Type annotations for
`aiobotocore.create_client("ec2").describe_instance_credit_specifications`
method.

Boto3 documentation:
[EC2.Client.describe_instance_credit_specifications](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_instance_credit_specifications)

Asynchronous method. Use `await describe_instance_credit_specifications(...)`
for a synchronous call.

Arguments mapping described in
[DescribeInstanceCreditSpecificationsRequestRequestTypeDef](./type_defs.md#describeinstancecreditspecificationsrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `InstanceIds`: `Sequence`\[`str`\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeInstanceCreditSpecificationsResultTypeDef](./type_defs.md#describeinstancecreditspecificationsresulttypedef).

<a id="describe_instance_event_notification_attributes"></a>

### describe_instance_event_notification_attributes

Describes the tag keys that are registered to appear in scheduled event
notifications for resources in the current Region.

Type annotations for
`aiobotocore.create_client("ec2").describe_instance_event_notification_attributes`
method.

Boto3 documentation:
[EC2.Client.describe_instance_event_notification_attributes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_instance_event_notification_attributes)

Asynchronous method. Use
`await describe_instance_event_notification_attributes(...)` for a synchronous
call.

Arguments mapping described in
[DescribeInstanceEventNotificationAttributesRequestRequestTypeDef](./type_defs.md#describeinstanceeventnotificationattributesrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeInstanceEventNotificationAttributesResultTypeDef](./type_defs.md#describeinstanceeventnotificationattributesresulttypedef).

<a id="describe_instance_event_windows"></a>

### describe_instance_event_windows

Describes the specified event windows or all event windows.

Type annotations for
`aiobotocore.create_client("ec2").describe_instance_event_windows` method.

Boto3 documentation:
[EC2.Client.describe_instance_event_windows](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_instance_event_windows)

Asynchronous method. Use `await describe_instance_event_windows(...)` for a
synchronous call.

Arguments mapping described in
[DescribeInstanceEventWindowsRequestRequestTypeDef](./type_defs.md#describeinstanceeventwindowsrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `InstanceEventWindowIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeInstanceEventWindowsResultTypeDef](./type_defs.md#describeinstanceeventwindowsresulttypedef).

<a id="describe_instance_status"></a>

### describe_instance_status

Describes the status of the specified instances or all of your instances.

Type annotations for
`aiobotocore.create_client("ec2").describe_instance_status` method.

Boto3 documentation:
[EC2.Client.describe_instance_status](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_instance_status)

Asynchronous method. Use `await describe_instance_status(...)` for a
synchronous call.

Arguments mapping described in
[DescribeInstanceStatusRequestRequestTypeDef](./type_defs.md#describeinstancestatusrequestrequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `InstanceIds`: `Sequence`\[`str`\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `DryRun`: `bool`
- `IncludeAllInstances`: `bool`

Returns a `Coroutine` for
[DescribeInstanceStatusResultTypeDef](./type_defs.md#describeinstancestatusresulttypedef).

<a id="describe_instance_type_offerings"></a>

### describe_instance_type_offerings

Returns a list of all instance types offered.

Type annotations for
`aiobotocore.create_client("ec2").describe_instance_type_offerings` method.

Boto3 documentation:
[EC2.Client.describe_instance_type_offerings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_instance_type_offerings)

Asynchronous method. Use `await describe_instance_type_offerings(...)` for a
synchronous call.

Arguments mapping described in
[DescribeInstanceTypeOfferingsRequestRequestTypeDef](./type_defs.md#describeinstancetypeofferingsrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `LocationType`: [LocationTypeType](./literals.md#locationtypetype)
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeInstanceTypeOfferingsResultTypeDef](./type_defs.md#describeinstancetypeofferingsresulttypedef).

<a id="describe_instance_types"></a>

### describe_instance_types

Describes the details of the instance types that are offered in a location.

Type annotations for `aiobotocore.create_client("ec2").describe_instance_types`
method.

Boto3 documentation:
[EC2.Client.describe_instance_types](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_instance_types)

Asynchronous method. Use `await describe_instance_types(...)` for a synchronous
call.

Arguments mapping described in
[DescribeInstanceTypesRequestRequestTypeDef](./type_defs.md#describeinstancetypesrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `InstanceTypes`:
  `Sequence`\[[InstanceTypeType](./literals.md#instancetypetype)\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeInstanceTypesResultTypeDef](./type_defs.md#describeinstancetypesresulttypedef).

<a id="describe_instances"></a>

### describe_instances

Describes the specified instances or all instances.

Type annotations for `aiobotocore.create_client("ec2").describe_instances`
method.

Boto3 documentation:
[EC2.Client.describe_instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_instances)

Asynchronous method. Use `await describe_instances(...)` for a synchronous
call.

Arguments mapping described in
[DescribeInstancesRequestRequestTypeDef](./type_defs.md#describeinstancesrequestrequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `InstanceIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeInstancesResultTypeDef](./type_defs.md#describeinstancesresulttypedef).

<a id="describe_internet_gateways"></a>

### describe_internet_gateways

Describes one or more of your internet gateways.

Type annotations for
`aiobotocore.create_client("ec2").describe_internet_gateways` method.

Boto3 documentation:
[EC2.Client.describe_internet_gateways](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_internet_gateways)

Asynchronous method. Use `await describe_internet_gateways(...)` for a
synchronous call.

Arguments mapping described in
[DescribeInternetGatewaysRequestRequestTypeDef](./type_defs.md#describeinternetgatewaysrequestrequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `InternetGatewayIds`: `Sequence`\[`str`\]
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[DescribeInternetGatewaysResultTypeDef](./type_defs.md#describeinternetgatewaysresulttypedef).

<a id="describe_ipam_pools"></a>

### describe_ipam_pools

Get information about your IPAM pools.

Type annotations for `aiobotocore.create_client("ec2").describe_ipam_pools`
method.

Boto3 documentation:
[EC2.Client.describe_ipam_pools](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_ipam_pools)

Asynchronous method. Use `await describe_ipam_pools(...)` for a synchronous
call.

Arguments mapping described in
[DescribeIpamPoolsRequestRequestTypeDef](./type_defs.md#describeipampoolsrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `IpamPoolIds`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[DescribeIpamPoolsResultTypeDef](./type_defs.md#describeipampoolsresulttypedef).

<a id="describe_ipam_scopes"></a>

### describe_ipam_scopes

Get information about your IPAM scopes.

Type annotations for `aiobotocore.create_client("ec2").describe_ipam_scopes`
method.

Boto3 documentation:
[EC2.Client.describe_ipam_scopes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_ipam_scopes)

Asynchronous method. Use `await describe_ipam_scopes(...)` for a synchronous
call.

Arguments mapping described in
[DescribeIpamScopesRequestRequestTypeDef](./type_defs.md#describeipamscopesrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `IpamScopeIds`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[DescribeIpamScopesResultTypeDef](./type_defs.md#describeipamscopesresulttypedef).

<a id="describe_ipams"></a>

### describe_ipams

Get information about your IPAM pools.

Type annotations for `aiobotocore.create_client("ec2").describe_ipams` method.

Boto3 documentation:
[EC2.Client.describe_ipams](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_ipams)

Asynchronous method. Use `await describe_ipams(...)` for a synchronous call.

Arguments mapping described in
[DescribeIpamsRequestRequestTypeDef](./type_defs.md#describeipamsrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `IpamIds`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[DescribeIpamsResultTypeDef](./type_defs.md#describeipamsresulttypedef).

<a id="describe_ipv6_pools"></a>

### describe_ipv6_pools

Describes your IPv6 address pools.

Type annotations for `aiobotocore.create_client("ec2").describe_ipv6_pools`
method.

Boto3 documentation:
[EC2.Client.describe_ipv6_pools](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_ipv6_pools)

Asynchronous method. Use `await describe_ipv6_pools(...)` for a synchronous
call.

Arguments mapping described in
[DescribeIpv6PoolsRequestRequestTypeDef](./type_defs.md#describeipv6poolsrequestrequesttypedef).

Keyword-only arguments:

- `PoolIds`: `Sequence`\[`str`\]
- `NextToken`: `str`
- `MaxResults`: `int`
- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]

Returns a `Coroutine` for
[DescribeIpv6PoolsResultTypeDef](./type_defs.md#describeipv6poolsresulttypedef).

<a id="describe_key_pairs"></a>

### describe_key_pairs

Describes the specified key pairs or all of your key pairs.

Type annotations for `aiobotocore.create_client("ec2").describe_key_pairs`
method.

Boto3 documentation:
[EC2.Client.describe_key_pairs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_key_pairs)

Asynchronous method. Use `await describe_key_pairs(...)` for a synchronous
call.

Arguments mapping described in
[DescribeKeyPairsRequestRequestTypeDef](./type_defs.md#describekeypairsrequestrequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `KeyNames`: `Sequence`\[`str`\]
- `KeyPairIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeKeyPairsResultTypeDef](./type_defs.md#describekeypairsresulttypedef).

<a id="describe_launch_template_versions"></a>

### describe_launch_template_versions

Describes one or more versions of a specified launch template.

Type annotations for
`aiobotocore.create_client("ec2").describe_launch_template_versions` method.

Boto3 documentation:
[EC2.Client.describe_launch_template_versions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_launch_template_versions)

Asynchronous method. Use `await describe_launch_template_versions(...)` for a
synchronous call.

Arguments mapping described in
[DescribeLaunchTemplateVersionsRequestRequestTypeDef](./type_defs.md#describelaunchtemplateversionsrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `LaunchTemplateId`: `str`
- `LaunchTemplateName`: `str`
- `Versions`: `Sequence`\[`str`\]
- `MinVersion`: `str`
- `MaxVersion`: `str`
- `NextToken`: `str`
- `MaxResults`: `int`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]

Returns a `Coroutine` for
[DescribeLaunchTemplateVersionsResultTypeDef](./type_defs.md#describelaunchtemplateversionsresulttypedef).

<a id="describe_launch_templates"></a>

### describe_launch_templates

Describes one or more launch templates.

Type annotations for
`aiobotocore.create_client("ec2").describe_launch_templates` method.

Boto3 documentation:
[EC2.Client.describe_launch_templates](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_launch_templates)

Asynchronous method. Use `await describe_launch_templates(...)` for a
synchronous call.

Arguments mapping described in
[DescribeLaunchTemplatesRequestRequestTypeDef](./type_defs.md#describelaunchtemplatesrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `LaunchTemplateIds`: `Sequence`\[`str`\]
- `LaunchTemplateNames`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[DescribeLaunchTemplatesResultTypeDef](./type_defs.md#describelaunchtemplatesresulttypedef).

<a id="describe_local_gateway_route_table_virtual_interface_group_associations"></a>

### describe_local_gateway_route_table_virtual_interface_group_associations

Describes the associations between virtual interface groups and local gateway
route tables.

Type annotations for
`aiobotocore.create_client("ec2").describe_local_gateway_route_table_virtual_interface_group_associations`
method.

Boto3 documentation:
[EC2.Client.describe_local_gateway_route_table_virtual_interface_group_associations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_local_gateway_route_table_virtual_interface_group_associations)

Asynchronous method. Use
`await describe_local_gateway_route_table_virtual_interface_group_associations(...)`
for a synchronous call.

Arguments mapping described in
[DescribeLocalGatewayRouteTableVirtualInterfaceGroupAssociationsRequestRequestTypeDef](./type_defs.md#describelocalgatewayroutetablevirtualinterfacegroupassociationsrequestrequesttypedef).

Keyword-only arguments:

- `LocalGatewayRouteTableVirtualInterfaceGroupAssociationIds`:
  `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeLocalGatewayRouteTableVirtualInterfaceGroupAssociationsResultTypeDef](./type_defs.md#describelocalgatewayroutetablevirtualinterfacegroupassociationsresulttypedef).

<a id="describe_local_gateway_route_table_vpc_associations"></a>

### describe_local_gateway_route_table_vpc_associations

Describes the specified associations between VPCs and local gateway route
tables.

Type annotations for
`aiobotocore.create_client("ec2").describe_local_gateway_route_table_vpc_associations`
method.

Boto3 documentation:
[EC2.Client.describe_local_gateway_route_table_vpc_associations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_local_gateway_route_table_vpc_associations)

Asynchronous method. Use
`await describe_local_gateway_route_table_vpc_associations(...)` for a
synchronous call.

Arguments mapping described in
[DescribeLocalGatewayRouteTableVpcAssociationsRequestRequestTypeDef](./type_defs.md#describelocalgatewayroutetablevpcassociationsrequestrequesttypedef).

Keyword-only arguments:

- `LocalGatewayRouteTableVpcAssociationIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeLocalGatewayRouteTableVpcAssociationsResultTypeDef](./type_defs.md#describelocalgatewayroutetablevpcassociationsresulttypedef).

<a id="describe_local_gateway_route_tables"></a>

### describe_local_gateway_route_tables

Describes one or more local gateway route tables.

Type annotations for
`aiobotocore.create_client("ec2").describe_local_gateway_route_tables` method.

Boto3 documentation:
[EC2.Client.describe_local_gateway_route_tables](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_local_gateway_route_tables)

Asynchronous method. Use `await describe_local_gateway_route_tables(...)` for a
synchronous call.

Arguments mapping described in
[DescribeLocalGatewayRouteTablesRequestRequestTypeDef](./type_defs.md#describelocalgatewayroutetablesrequestrequesttypedef).

Keyword-only arguments:

- `LocalGatewayRouteTableIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeLocalGatewayRouteTablesResultTypeDef](./type_defs.md#describelocalgatewayroutetablesresulttypedef).

<a id="describe_local_gateway_virtual_interface_groups"></a>

### describe_local_gateway_virtual_interface_groups

Describes the specified local gateway virtual interface groups.

Type annotations for
`aiobotocore.create_client("ec2").describe_local_gateway_virtual_interface_groups`
method.

Boto3 documentation:
[EC2.Client.describe_local_gateway_virtual_interface_groups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_local_gateway_virtual_interface_groups)

Asynchronous method. Use
`await describe_local_gateway_virtual_interface_groups(...)` for a synchronous
call.

Arguments mapping described in
[DescribeLocalGatewayVirtualInterfaceGroupsRequestRequestTypeDef](./type_defs.md#describelocalgatewayvirtualinterfacegroupsrequestrequesttypedef).

Keyword-only arguments:

- `LocalGatewayVirtualInterfaceGroupIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeLocalGatewayVirtualInterfaceGroupsResultTypeDef](./type_defs.md#describelocalgatewayvirtualinterfacegroupsresulttypedef).

<a id="describe_local_gateway_virtual_interfaces"></a>

### describe_local_gateway_virtual_interfaces

Describes the specified local gateway virtual interfaces.

Type annotations for
`aiobotocore.create_client("ec2").describe_local_gateway_virtual_interfaces`
method.

Boto3 documentation:
[EC2.Client.describe_local_gateway_virtual_interfaces](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_local_gateway_virtual_interfaces)

Asynchronous method. Use `await describe_local_gateway_virtual_interfaces(...)`
for a synchronous call.

Arguments mapping described in
[DescribeLocalGatewayVirtualInterfacesRequestRequestTypeDef](./type_defs.md#describelocalgatewayvirtualinterfacesrequestrequesttypedef).

Keyword-only arguments:

- `LocalGatewayVirtualInterfaceIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeLocalGatewayVirtualInterfacesResultTypeDef](./type_defs.md#describelocalgatewayvirtualinterfacesresulttypedef).

<a id="describe_local_gateways"></a>

### describe_local_gateways

Describes one or more local gateways.

Type annotations for `aiobotocore.create_client("ec2").describe_local_gateways`
method.

Boto3 documentation:
[EC2.Client.describe_local_gateways](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_local_gateways)

Asynchronous method. Use `await describe_local_gateways(...)` for a synchronous
call.

Arguments mapping described in
[DescribeLocalGatewaysRequestRequestTypeDef](./type_defs.md#describelocalgatewaysrequestrequesttypedef).

Keyword-only arguments:

- `LocalGatewayIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeLocalGatewaysResultTypeDef](./type_defs.md#describelocalgatewaysresulttypedef).

<a id="describe_managed_prefix_lists"></a>

### describe_managed_prefix_lists

Describes your managed prefix lists and any Amazon Web Services-managed prefix
lists.

Type annotations for
`aiobotocore.create_client("ec2").describe_managed_prefix_lists` method.

Boto3 documentation:
[EC2.Client.describe_managed_prefix_lists](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_managed_prefix_lists)

Asynchronous method. Use `await describe_managed_prefix_lists(...)` for a
synchronous call.

Arguments mapping described in
[DescribeManagedPrefixListsRequestRequestTypeDef](./type_defs.md#describemanagedprefixlistsrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `PrefixListIds`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[DescribeManagedPrefixListsResultTypeDef](./type_defs.md#describemanagedprefixlistsresulttypedef).

<a id="describe_moving_addresses"></a>

### describe_moving_addresses

Describes your Elastic IP addresses that are being moved to the EC2-VPC
platform, or that are being restored to the EC2-Classic platform.

Type annotations for
`aiobotocore.create_client("ec2").describe_moving_addresses` method.

Boto3 documentation:
[EC2.Client.describe_moving_addresses](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_moving_addresses)

Asynchronous method. Use `await describe_moving_addresses(...)` for a
synchronous call.

Arguments mapping described in
[DescribeMovingAddressesRequestRequestTypeDef](./type_defs.md#describemovingaddressesrequestrequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `MaxResults`: `int`
- `NextToken`: `str`
- `PublicIps`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[DescribeMovingAddressesResultTypeDef](./type_defs.md#describemovingaddressesresulttypedef).

<a id="describe_nat_gateways"></a>

### describe_nat_gateways

Describes one or more of your NAT gateways.

Type annotations for `aiobotocore.create_client("ec2").describe_nat_gateways`
method.

Boto3 documentation:
[EC2.Client.describe_nat_gateways](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_nat_gateways)

Asynchronous method. Use `await describe_nat_gateways(...)` for a synchronous
call.

Arguments mapping described in
[DescribeNatGatewaysRequestRequestTypeDef](./type_defs.md#describenatgatewaysrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NatGatewayIds`: `Sequence`\[`str`\]
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeNatGatewaysResultTypeDef](./type_defs.md#describenatgatewaysresulttypedef).

<a id="describe_network_acls"></a>

### describe_network_acls

Describes one or more of your network ACLs.

Type annotations for `aiobotocore.create_client("ec2").describe_network_acls`
method.

Boto3 documentation:
[EC2.Client.describe_network_acls](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_network_acls)

Asynchronous method. Use `await describe_network_acls(...)` for a synchronous
call.

Arguments mapping described in
[DescribeNetworkAclsRequestRequestTypeDef](./type_defs.md#describenetworkaclsrequestrequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `NetworkAclIds`: `Sequence`\[`str`\]
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[DescribeNetworkAclsResultTypeDef](./type_defs.md#describenetworkaclsresulttypedef).

<a id="describe_network_insights_access_scope_analyses"></a>

### describe_network_insights_access_scope_analyses

Describes the specified Network Access Scope analyses.

Type annotations for
`aiobotocore.create_client("ec2").describe_network_insights_access_scope_analyses`
method.

Boto3 documentation:
[EC2.Client.describe_network_insights_access_scope_analyses](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_network_insights_access_scope_analyses)

Asynchronous method. Use
`await describe_network_insights_access_scope_analyses(...)` for a synchronous
call.

Arguments mapping described in
[DescribeNetworkInsightsAccessScopeAnalysesRequestRequestTypeDef](./type_defs.md#describenetworkinsightsaccessscopeanalysesrequestrequesttypedef).

Keyword-only arguments:

- `NetworkInsightsAccessScopeAnalysisIds`: `Sequence`\[`str`\]
- `NetworkInsightsAccessScopeId`: `str`
- `AnalysisStartTimeBegin`: `Union`\[`datetime`, `str`\]
- `AnalysisStartTimeEnd`: `Union`\[`datetime`, `str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `DryRun`: `bool`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeNetworkInsightsAccessScopeAnalysesResultTypeDef](./type_defs.md#describenetworkinsightsaccessscopeanalysesresulttypedef).

<a id="describe_network_insights_access_scopes"></a>

### describe_network_insights_access_scopes

Describes the specified Network Access Scopes.

Type annotations for
`aiobotocore.create_client("ec2").describe_network_insights_access_scopes`
method.

Boto3 documentation:
[EC2.Client.describe_network_insights_access_scopes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_network_insights_access_scopes)

Asynchronous method. Use `await describe_network_insights_access_scopes(...)`
for a synchronous call.

Arguments mapping described in
[DescribeNetworkInsightsAccessScopesRequestRequestTypeDef](./type_defs.md#describenetworkinsightsaccessscopesrequestrequesttypedef).

Keyword-only arguments:

- `NetworkInsightsAccessScopeIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `DryRun`: `bool`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeNetworkInsightsAccessScopesResultTypeDef](./type_defs.md#describenetworkinsightsaccessscopesresulttypedef).

<a id="describe_network_insights_analyses"></a>

### describe_network_insights_analyses

Describes one or more of your network insights analyses.

Type annotations for
`aiobotocore.create_client("ec2").describe_network_insights_analyses` method.

Boto3 documentation:
[EC2.Client.describe_network_insights_analyses](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_network_insights_analyses)

Asynchronous method. Use `await describe_network_insights_analyses(...)` for a
synchronous call.

Arguments mapping described in
[DescribeNetworkInsightsAnalysesRequestRequestTypeDef](./type_defs.md#describenetworkinsightsanalysesrequestrequesttypedef).

Keyword-only arguments:

- `NetworkInsightsAnalysisIds`: `Sequence`\[`str`\]
- `NetworkInsightsPathId`: `str`
- `AnalysisStartTime`: `Union`\[`datetime`, `str`\]
- `AnalysisEndTime`: `Union`\[`datetime`, `str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `DryRun`: `bool`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeNetworkInsightsAnalysesResultTypeDef](./type_defs.md#describenetworkinsightsanalysesresulttypedef).

<a id="describe_network_insights_paths"></a>

### describe_network_insights_paths

Describes one or more of your paths.

Type annotations for
`aiobotocore.create_client("ec2").describe_network_insights_paths` method.

Boto3 documentation:
[EC2.Client.describe_network_insights_paths](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_network_insights_paths)

Asynchronous method. Use `await describe_network_insights_paths(...)` for a
synchronous call.

Arguments mapping described in
[DescribeNetworkInsightsPathsRequestRequestTypeDef](./type_defs.md#describenetworkinsightspathsrequestrequesttypedef).

Keyword-only arguments:

- `NetworkInsightsPathIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `DryRun`: `bool`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeNetworkInsightsPathsResultTypeDef](./type_defs.md#describenetworkinsightspathsresulttypedef).

<a id="describe_network_interface_attribute"></a>

### describe_network_interface_attribute

Describes a network interface attribute.

Type annotations for
`aiobotocore.create_client("ec2").describe_network_interface_attribute` method.

Boto3 documentation:
[EC2.Client.describe_network_interface_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_network_interface_attribute)

Asynchronous method. Use `await describe_network_interface_attribute(...)` for
a synchronous call.

Arguments mapping described in
[DescribeNetworkInterfaceAttributeRequestRequestTypeDef](./type_defs.md#describenetworkinterfaceattributerequestrequesttypedef).

Keyword-only arguments:

- `NetworkInterfaceId`: `str` *(required)*
- `Attribute`:
  [NetworkInterfaceAttributeType](./literals.md#networkinterfaceattributetype)
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeNetworkInterfaceAttributeResultTypeDef](./type_defs.md#describenetworkinterfaceattributeresulttypedef).

<a id="describe_network_interface_permissions"></a>

### describe_network_interface_permissions

Describes the permissions for your network interfaces.

Type annotations for
`aiobotocore.create_client("ec2").describe_network_interface_permissions`
method.

Boto3 documentation:
[EC2.Client.describe_network_interface_permissions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_network_interface_permissions)

Asynchronous method. Use `await describe_network_interface_permissions(...)`
for a synchronous call.

Arguments mapping described in
[DescribeNetworkInterfacePermissionsRequestRequestTypeDef](./type_defs.md#describenetworkinterfacepermissionsrequestrequesttypedef).

Keyword-only arguments:

- `NetworkInterfacePermissionIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[DescribeNetworkInterfacePermissionsResultTypeDef](./type_defs.md#describenetworkinterfacepermissionsresulttypedef).

<a id="describe_network_interfaces"></a>

### describe_network_interfaces

Describes one or more of your network interfaces.

Type annotations for
`aiobotocore.create_client("ec2").describe_network_interfaces` method.

Boto3 documentation:
[EC2.Client.describe_network_interfaces](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_network_interfaces)

Asynchronous method. Use `await describe_network_interfaces(...)` for a
synchronous call.

Arguments mapping described in
[DescribeNetworkInterfacesRequestRequestTypeDef](./type_defs.md#describenetworkinterfacesrequestrequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `NetworkInterfaceIds`: `Sequence`\[`str`\]
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[DescribeNetworkInterfacesResultTypeDef](./type_defs.md#describenetworkinterfacesresulttypedef).

<a id="describe_placement_groups"></a>

### describe_placement_groups

Describes the specified placement groups or all of your placement groups.

Type annotations for
`aiobotocore.create_client("ec2").describe_placement_groups` method.

Boto3 documentation:
[EC2.Client.describe_placement_groups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_placement_groups)

Asynchronous method. Use `await describe_placement_groups(...)` for a
synchronous call.

Arguments mapping described in
[DescribePlacementGroupsRequestRequestTypeDef](./type_defs.md#describeplacementgroupsrequestrequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `GroupNames`: `Sequence`\[`str`\]
- `GroupIds`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[DescribePlacementGroupsResultTypeDef](./type_defs.md#describeplacementgroupsresulttypedef).

<a id="describe_prefix_lists"></a>

### describe_prefix_lists

Describes available Amazon Web Services services in a prefix list format, which
includes the prefix list name and prefix list ID of the service and the IP
address range for the service.

Type annotations for `aiobotocore.create_client("ec2").describe_prefix_lists`
method.

Boto3 documentation:
[EC2.Client.describe_prefix_lists](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_prefix_lists)

Asynchronous method. Use `await describe_prefix_lists(...)` for a synchronous
call.

Arguments mapping described in
[DescribePrefixListsRequestRequestTypeDef](./type_defs.md#describeprefixlistsrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `PrefixListIds`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[DescribePrefixListsResultTypeDef](./type_defs.md#describeprefixlistsresulttypedef).

<a id="describe_principal_id_format"></a>

### describe_principal_id_format

Describes the ID format settings for the root user and all IAM roles and IAM
users that have explicitly specified a longer ID (17-character ID) preference.

Type annotations for
`aiobotocore.create_client("ec2").describe_principal_id_format` method.

Boto3 documentation:
[EC2.Client.describe_principal_id_format](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_principal_id_format)

Asynchronous method. Use `await describe_principal_id_format(...)` for a
synchronous call.

Arguments mapping described in
[DescribePrincipalIdFormatRequestRequestTypeDef](./type_defs.md#describeprincipalidformatrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `Resources`: `Sequence`\[`str`\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribePrincipalIdFormatResultTypeDef](./type_defs.md#describeprincipalidformatresulttypedef).

<a id="describe_public_ipv4_pools"></a>

### describe_public_ipv4_pools

Describes the specified IPv4 address pools.

Type annotations for
`aiobotocore.create_client("ec2").describe_public_ipv4_pools` method.

Boto3 documentation:
[EC2.Client.describe_public_ipv4_pools](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_public_ipv4_pools)

Asynchronous method. Use `await describe_public_ipv4_pools(...)` for a
synchronous call.

Arguments mapping described in
[DescribePublicIpv4PoolsRequestRequestTypeDef](./type_defs.md#describepublicipv4poolsrequestrequesttypedef).

Keyword-only arguments:

- `PoolIds`: `Sequence`\[`str`\]
- `NextToken`: `str`
- `MaxResults`: `int`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]

Returns a `Coroutine` for
[DescribePublicIpv4PoolsResultTypeDef](./type_defs.md#describepublicipv4poolsresulttypedef).

<a id="describe_regions"></a>

### describe_regions

Describes the Regions that are enabled for your account, or all Regions.

Type annotations for `aiobotocore.create_client("ec2").describe_regions`
method.

Boto3 documentation:
[EC2.Client.describe_regions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_regions)

Asynchronous method. Use `await describe_regions(...)` for a synchronous call.

Arguments mapping described in
[DescribeRegionsRequestRequestTypeDef](./type_defs.md#describeregionsrequestrequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `RegionNames`: `Sequence`\[`str`\]
- `DryRun`: `bool`
- `AllRegions`: `bool`

Returns a `Coroutine` for
[DescribeRegionsResultTypeDef](./type_defs.md#describeregionsresulttypedef).

<a id="describe_replace_root_volume_tasks"></a>

### describe_replace_root_volume_tasks

Describes a root volume replacement task.

Type annotations for
`aiobotocore.create_client("ec2").describe_replace_root_volume_tasks` method.

Boto3 documentation:
[EC2.Client.describe_replace_root_volume_tasks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_replace_root_volume_tasks)

Asynchronous method. Use `await describe_replace_root_volume_tasks(...)` for a
synchronous call.

Arguments mapping described in
[DescribeReplaceRootVolumeTasksRequestRequestTypeDef](./type_defs.md#describereplacerootvolumetasksrequestrequesttypedef).

Keyword-only arguments:

- `ReplaceRootVolumeTaskIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeReplaceRootVolumeTasksResultTypeDef](./type_defs.md#describereplacerootvolumetasksresulttypedef).

<a id="describe_reserved_instances"></a>

### describe_reserved_instances

Describes one or more of the Reserved Instances that you purchased.

Type annotations for
`aiobotocore.create_client("ec2").describe_reserved_instances` method.

Boto3 documentation:
[EC2.Client.describe_reserved_instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_reserved_instances)

Asynchronous method. Use `await describe_reserved_instances(...)` for a
synchronous call.

Arguments mapping described in
[DescribeReservedInstancesRequestRequestTypeDef](./type_defs.md#describereservedinstancesrequestrequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `OfferingClass`: [OfferingClassTypeType](./literals.md#offeringclasstypetype)
- `ReservedInstancesIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`
- `OfferingType`:
  [OfferingTypeValuesType](./literals.md#offeringtypevaluestype)

Returns a `Coroutine` for
[DescribeReservedInstancesResultTypeDef](./type_defs.md#describereservedinstancesresulttypedef).

<a id="describe_reserved_instances_listings"></a>

### describe_reserved_instances_listings

Describes your account's Reserved Instance listings in the Reserved Instance
Marketplace.

Type annotations for
`aiobotocore.create_client("ec2").describe_reserved_instances_listings` method.

Boto3 documentation:
[EC2.Client.describe_reserved_instances_listings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_reserved_instances_listings)

Asynchronous method. Use `await describe_reserved_instances_listings(...)` for
a synchronous call.

Arguments mapping described in
[DescribeReservedInstancesListingsRequestRequestTypeDef](./type_defs.md#describereservedinstanceslistingsrequestrequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `ReservedInstancesId`: `str`
- `ReservedInstancesListingId`: `str`

Returns a `Coroutine` for
[DescribeReservedInstancesListingsResultTypeDef](./type_defs.md#describereservedinstanceslistingsresulttypedef).

<a id="describe_reserved_instances_modifications"></a>

### describe_reserved_instances_modifications

Describes the modifications made to your Reserved Instances.

Type annotations for
`aiobotocore.create_client("ec2").describe_reserved_instances_modifications`
method.

Boto3 documentation:
[EC2.Client.describe_reserved_instances_modifications](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_reserved_instances_modifications)

Asynchronous method. Use `await describe_reserved_instances_modifications(...)`
for a synchronous call.

Arguments mapping described in
[DescribeReservedInstancesModificationsRequestRequestTypeDef](./type_defs.md#describereservedinstancesmodificationsrequestrequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `ReservedInstancesModificationIds`: `Sequence`\[`str`\]
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeReservedInstancesModificationsResultTypeDef](./type_defs.md#describereservedinstancesmodificationsresulttypedef).

<a id="describe_reserved_instances_offerings"></a>

### describe_reserved_instances_offerings

Describes Reserved Instance offerings that are available for purchase.

Type annotations for
`aiobotocore.create_client("ec2").describe_reserved_instances_offerings`
method.

Boto3 documentation:
[EC2.Client.describe_reserved_instances_offerings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_reserved_instances_offerings)

Asynchronous method. Use `await describe_reserved_instances_offerings(...)` for
a synchronous call.

Arguments mapping described in
[DescribeReservedInstancesOfferingsRequestRequestTypeDef](./type_defs.md#describereservedinstancesofferingsrequestrequesttypedef).

Keyword-only arguments:

- `AvailabilityZone`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `IncludeMarketplace`: `bool`
- `InstanceType`: [InstanceTypeType](./literals.md#instancetypetype)
- `MaxDuration`: `int`
- `MaxInstanceCount`: `int`
- `MinDuration`: `int`
- `OfferingClass`: [OfferingClassTypeType](./literals.md#offeringclasstypetype)
- `ProductDescription`:
  [RIProductDescriptionType](./literals.md#riproductdescriptiontype)
- `ReservedInstancesOfferingIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`
- `InstanceTenancy`: [TenancyType](./literals.md#tenancytype)
- `MaxResults`: `int`
- `NextToken`: `str`
- `OfferingType`:
  [OfferingTypeValuesType](./literals.md#offeringtypevaluestype)

Returns a `Coroutine` for
[DescribeReservedInstancesOfferingsResultTypeDef](./type_defs.md#describereservedinstancesofferingsresulttypedef).

<a id="describe_route_tables"></a>

### describe_route_tables

Describes one or more of your route tables.

Type annotations for `aiobotocore.create_client("ec2").describe_route_tables`
method.

Boto3 documentation:
[EC2.Client.describe_route_tables](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_route_tables)

Asynchronous method. Use `await describe_route_tables(...)` for a synchronous
call.

Arguments mapping described in
[DescribeRouteTablesRequestRequestTypeDef](./type_defs.md#describeroutetablesrequestrequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `RouteTableIds`: `Sequence`\[`str`\]
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[DescribeRouteTablesResultTypeDef](./type_defs.md#describeroutetablesresulttypedef).

<a id="describe_scheduled_instance_availability"></a>

### describe_scheduled_instance_availability

Finds available schedules that meet the specified criteria.

Type annotations for
`aiobotocore.create_client("ec2").describe_scheduled_instance_availability`
method.

Boto3 documentation:
[EC2.Client.describe_scheduled_instance_availability](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_scheduled_instance_availability)

Asynchronous method. Use `await describe_scheduled_instance_availability(...)`
for a synchronous call.

Arguments mapping described in
[DescribeScheduledInstanceAvailabilityRequestRequestTypeDef](./type_defs.md#describescheduledinstanceavailabilityrequestrequesttypedef).

Keyword-only arguments:

- `FirstSlotStartTimeRange`:
  [SlotDateTimeRangeRequestTypeDef](./type_defs.md#slotdatetimerangerequesttypedef)
  *(required)*
- `Recurrence`:
  [ScheduledInstanceRecurrenceRequestTypeDef](./type_defs.md#scheduledinstancerecurrencerequesttypedef)
  *(required)*
- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `MaxSlotDurationInHours`: `int`
- `MinSlotDurationInHours`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeScheduledInstanceAvailabilityResultTypeDef](./type_defs.md#describescheduledinstanceavailabilityresulttypedef).

<a id="describe_scheduled_instances"></a>

### describe_scheduled_instances

Describes the specified Scheduled Instances or all your Scheduled Instances.

Type annotations for
`aiobotocore.create_client("ec2").describe_scheduled_instances` method.

Boto3 documentation:
[EC2.Client.describe_scheduled_instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_scheduled_instances)

Asynchronous method. Use `await describe_scheduled_instances(...)` for a
synchronous call.

Arguments mapping described in
[DescribeScheduledInstancesRequestRequestTypeDef](./type_defs.md#describescheduledinstancesrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `ScheduledInstanceIds`: `Sequence`\[`str`\]
- `SlotStartTimeRange`:
  [SlotStartTimeRangeRequestTypeDef](./type_defs.md#slotstarttimerangerequesttypedef)

Returns a `Coroutine` for
[DescribeScheduledInstancesResultTypeDef](./type_defs.md#describescheduledinstancesresulttypedef).

<a id="describe_security_group_references"></a>

### describe_security_group_references

Type annotations for
`aiobotocore.create_client("ec2").describe_security_group_references` method.

Boto3 documentation:
[EC2.Client.describe_security_group_references](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_security_group_references)

Asynchronous method. Use `await describe_security_group_references(...)` for a
synchronous call.

Arguments mapping described in
[DescribeSecurityGroupReferencesRequestRequestTypeDef](./type_defs.md#describesecuritygroupreferencesrequestrequesttypedef).

Keyword-only arguments:

- `GroupId`: `Sequence`\[`str`\] *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeSecurityGroupReferencesResultTypeDef](./type_defs.md#describesecuritygroupreferencesresulttypedef).

<a id="describe_security_group_rules"></a>

### describe_security_group_rules

Describes one or more of your security group rules.

Type annotations for
`aiobotocore.create_client("ec2").describe_security_group_rules` method.

Boto3 documentation:
[EC2.Client.describe_security_group_rules](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_security_group_rules)

Asynchronous method. Use `await describe_security_group_rules(...)` for a
synchronous call.

Arguments mapping described in
[DescribeSecurityGroupRulesRequestRequestTypeDef](./type_defs.md#describesecuritygrouprulesrequestrequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `SecurityGroupRuleIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[DescribeSecurityGroupRulesResultTypeDef](./type_defs.md#describesecuritygrouprulesresulttypedef).

<a id="describe_security_groups"></a>

### describe_security_groups

Describes the specified security groups or all of your security groups.

Type annotations for
`aiobotocore.create_client("ec2").describe_security_groups` method.

Boto3 documentation:
[EC2.Client.describe_security_groups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_security_groups)

Asynchronous method. Use `await describe_security_groups(...)` for a
synchronous call.

Arguments mapping described in
[DescribeSecurityGroupsRequestRequestTypeDef](./type_defs.md#describesecuritygroupsrequestrequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `GroupIds`: `Sequence`\[`str`\]
- `GroupNames`: `Sequence`\[`str`\]
- `DryRun`: `bool`
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[DescribeSecurityGroupsResultTypeDef](./type_defs.md#describesecuritygroupsresulttypedef).

<a id="describe_snapshot_attribute"></a>

### describe_snapshot_attribute

Describes the specified attribute of the specified snapshot.

Type annotations for
`aiobotocore.create_client("ec2").describe_snapshot_attribute` method.

Boto3 documentation:
[EC2.Client.describe_snapshot_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_snapshot_attribute)

Asynchronous method. Use `await describe_snapshot_attribute(...)` for a
synchronous call.

Arguments mapping described in
[DescribeSnapshotAttributeRequestRequestTypeDef](./type_defs.md#describesnapshotattributerequestrequesttypedef).

Keyword-only arguments:

- `Attribute`:
  [SnapshotAttributeNameType](./literals.md#snapshotattributenametype)
  *(required)*
- `SnapshotId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeSnapshotAttributeResultTypeDef](./type_defs.md#describesnapshotattributeresulttypedef).

<a id="describe_snapshot_tier_status"></a>

### describe_snapshot_tier_status

Describes the storage tier status of one or more Amazon EBS snapshots.

Type annotations for
`aiobotocore.create_client("ec2").describe_snapshot_tier_status` method.

Boto3 documentation:
[EC2.Client.describe_snapshot_tier_status](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_snapshot_tier_status)

Asynchronous method. Use `await describe_snapshot_tier_status(...)` for a
synchronous call.

Arguments mapping described in
[DescribeSnapshotTierStatusRequestRequestTypeDef](./type_defs.md#describesnapshottierstatusrequestrequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[DescribeSnapshotTierStatusResultTypeDef](./type_defs.md#describesnapshottierstatusresulttypedef).

<a id="describe_snapshots"></a>

### describe_snapshots

Describes the specified EBS snapshots available to you or all of the EBS
snapshots available to you.

Type annotations for `aiobotocore.create_client("ec2").describe_snapshots`
method.

Boto3 documentation:
[EC2.Client.describe_snapshots](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_snapshots)

Asynchronous method. Use `await describe_snapshots(...)` for a synchronous
call.

Arguments mapping described in
[DescribeSnapshotsRequestRequestTypeDef](./type_defs.md#describesnapshotsrequestrequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `OwnerIds`: `Sequence`\[`str`\]
- `RestorableByUserIds`: `Sequence`\[`str`\]
- `SnapshotIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeSnapshotsResultTypeDef](./type_defs.md#describesnapshotsresulttypedef).

<a id="describe_spot_datafeed_subscription"></a>

### describe_spot_datafeed_subscription

Describes the data feed for Spot Instances.

Type annotations for
`aiobotocore.create_client("ec2").describe_spot_datafeed_subscription` method.

Boto3 documentation:
[EC2.Client.describe_spot_datafeed_subscription](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_spot_datafeed_subscription)

Asynchronous method. Use `await describe_spot_datafeed_subscription(...)` for a
synchronous call.

Arguments mapping described in
[DescribeSpotDatafeedSubscriptionRequestRequestTypeDef](./type_defs.md#describespotdatafeedsubscriptionrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeSpotDatafeedSubscriptionResultTypeDef](./type_defs.md#describespotdatafeedsubscriptionresulttypedef).

<a id="describe_spot_fleet_instances"></a>

### describe_spot_fleet_instances

Describes the running instances for the specified Spot Fleet.

Type annotations for
`aiobotocore.create_client("ec2").describe_spot_fleet_instances` method.

Boto3 documentation:
[EC2.Client.describe_spot_fleet_instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_spot_fleet_instances)

Asynchronous method. Use `await describe_spot_fleet_instances(...)` for a
synchronous call.

Arguments mapping described in
[DescribeSpotFleetInstancesRequestRequestTypeDef](./type_defs.md#describespotfleetinstancesrequestrequesttypedef).

Keyword-only arguments:

- `SpotFleetRequestId`: `str` *(required)*
- `DryRun`: `bool`
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeSpotFleetInstancesResponseTypeDef](./type_defs.md#describespotfleetinstancesresponsetypedef).

<a id="describe_spot_fleet_request_history"></a>

### describe_spot_fleet_request_history

Describes the events for the specified Spot Fleet request during the specified
time.

Type annotations for
`aiobotocore.create_client("ec2").describe_spot_fleet_request_history` method.

Boto3 documentation:
[EC2.Client.describe_spot_fleet_request_history](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_spot_fleet_request_history)

Asynchronous method. Use `await describe_spot_fleet_request_history(...)` for a
synchronous call.

Arguments mapping described in
[DescribeSpotFleetRequestHistoryRequestRequestTypeDef](./type_defs.md#describespotfleetrequesthistoryrequestrequesttypedef).

Keyword-only arguments:

- `SpotFleetRequestId`: `str` *(required)*
- `StartTime`: `Union`\[`datetime`, `str`\] *(required)*
- `DryRun`: `bool`
- `EventType`: [EventTypeType](./literals.md#eventtypetype)
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeSpotFleetRequestHistoryResponseTypeDef](./type_defs.md#describespotfleetrequesthistoryresponsetypedef).

<a id="describe_spot_fleet_requests"></a>

### describe_spot_fleet_requests

.

Type annotations for
`aiobotocore.create_client("ec2").describe_spot_fleet_requests` method.

Boto3 documentation:
[EC2.Client.describe_spot_fleet_requests](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_spot_fleet_requests)

Asynchronous method. Use `await describe_spot_fleet_requests(...)` for a
synchronous call.

Arguments mapping described in
[DescribeSpotFleetRequestsRequestRequestTypeDef](./type_defs.md#describespotfleetrequestsrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `MaxResults`: `int`
- `NextToken`: `str`
- `SpotFleetRequestIds`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[DescribeSpotFleetRequestsResponseTypeDef](./type_defs.md#describespotfleetrequestsresponsetypedef).

<a id="describe_spot_instance_requests"></a>

### describe_spot_instance_requests

Describes the specified Spot Instance requests.

Type annotations for
`aiobotocore.create_client("ec2").describe_spot_instance_requests` method.

Boto3 documentation:
[EC2.Client.describe_spot_instance_requests](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_spot_instance_requests)

Asynchronous method. Use `await describe_spot_instance_requests(...)` for a
synchronous call.

Arguments mapping described in
[DescribeSpotInstanceRequestsRequestRequestTypeDef](./type_defs.md#describespotinstancerequestsrequestrequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `SpotInstanceRequestIds`: `Sequence`\[`str`\]
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[DescribeSpotInstanceRequestsResultTypeDef](./type_defs.md#describespotinstancerequestsresulttypedef).

<a id="describe_spot_price_history"></a>

### describe_spot_price_history

Describes the Spot price history.

Type annotations for
`aiobotocore.create_client("ec2").describe_spot_price_history` method.

Boto3 documentation:
[EC2.Client.describe_spot_price_history](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_spot_price_history)

Asynchronous method. Use `await describe_spot_price_history(...)` for a
synchronous call.

Arguments mapping described in
[DescribeSpotPriceHistoryRequestRequestTypeDef](./type_defs.md#describespotpricehistoryrequestrequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `AvailabilityZone`: `str`
- `DryRun`: `bool`
- `EndTime`: `Union`\[`datetime`, `str`\]
- `InstanceTypes`:
  `Sequence`\[[InstanceTypeType](./literals.md#instancetypetype)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `ProductDescriptions`: `Sequence`\[`str`\]
- `StartTime`: `Union`\[`datetime`, `str`\]

Returns a `Coroutine` for
[DescribeSpotPriceHistoryResultTypeDef](./type_defs.md#describespotpricehistoryresulttypedef).

<a id="describe_stale_security_groups"></a>

### describe_stale_security_groups

Type annotations for
`aiobotocore.create_client("ec2").describe_stale_security_groups` method.

Boto3 documentation:
[EC2.Client.describe_stale_security_groups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_stale_security_groups)

Asynchronous method. Use `await describe_stale_security_groups(...)` for a
synchronous call.

Arguments mapping described in
[DescribeStaleSecurityGroupsRequestRequestTypeDef](./type_defs.md#describestalesecuritygroupsrequestrequesttypedef).

Keyword-only arguments:

- `VpcId`: `str` *(required)*
- `DryRun`: `bool`
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeStaleSecurityGroupsResultTypeDef](./type_defs.md#describestalesecuritygroupsresulttypedef).

<a id="describe_store_image_tasks"></a>

### describe_store_image_tasks

Describes the progress of the AMI store tasks.

Type annotations for
`aiobotocore.create_client("ec2").describe_store_image_tasks` method.

Boto3 documentation:
[EC2.Client.describe_store_image_tasks](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_store_image_tasks)

Asynchronous method. Use `await describe_store_image_tasks(...)` for a
synchronous call.

Arguments mapping described in
[DescribeStoreImageTasksRequestRequestTypeDef](./type_defs.md#describestoreimagetasksrequestrequesttypedef).

Keyword-only arguments:

- `ImageIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[DescribeStoreImageTasksResultTypeDef](./type_defs.md#describestoreimagetasksresulttypedef).

<a id="describe_subnets"></a>

### describe_subnets

Describes one or more of your subnets.

Type annotations for `aiobotocore.create_client("ec2").describe_subnets`
method.

Boto3 documentation:
[EC2.Client.describe_subnets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_subnets)

Asynchronous method. Use `await describe_subnets(...)` for a synchronous call.

Arguments mapping described in
[DescribeSubnetsRequestRequestTypeDef](./type_defs.md#describesubnetsrequestrequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `SubnetIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[DescribeSubnetsResultTypeDef](./type_defs.md#describesubnetsresulttypedef).

<a id="describe_tags"></a>

### describe_tags

Describes the specified tags for your EC2 resources.

Type annotations for `aiobotocore.create_client("ec2").describe_tags` method.

Boto3 documentation:
[EC2.Client.describe_tags](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_tags)

Asynchronous method. Use `await describe_tags(...)` for a synchronous call.

Arguments mapping described in
[DescribeTagsRequestRequestTypeDef](./type_defs.md#describetagsrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeTagsResultTypeDef](./type_defs.md#describetagsresulttypedef).

<a id="describe_traffic_mirror_filters"></a>

### describe_traffic_mirror_filters

Describes one or more Traffic Mirror filters.

Type annotations for
`aiobotocore.create_client("ec2").describe_traffic_mirror_filters` method.

Boto3 documentation:
[EC2.Client.describe_traffic_mirror_filters](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_traffic_mirror_filters)

Asynchronous method. Use `await describe_traffic_mirror_filters(...)` for a
synchronous call.

Arguments mapping described in
[DescribeTrafficMirrorFiltersRequestRequestTypeDef](./type_defs.md#describetrafficmirrorfiltersrequestrequesttypedef).

Keyword-only arguments:

- `TrafficMirrorFilterIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeTrafficMirrorFiltersResultTypeDef](./type_defs.md#describetrafficmirrorfiltersresulttypedef).

<a id="describe_traffic_mirror_sessions"></a>

### describe_traffic_mirror_sessions

Describes one or more Traffic Mirror sessions.

Type annotations for
`aiobotocore.create_client("ec2").describe_traffic_mirror_sessions` method.

Boto3 documentation:
[EC2.Client.describe_traffic_mirror_sessions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_traffic_mirror_sessions)

Asynchronous method. Use `await describe_traffic_mirror_sessions(...)` for a
synchronous call.

Arguments mapping described in
[DescribeTrafficMirrorSessionsRequestRequestTypeDef](./type_defs.md#describetrafficmirrorsessionsrequestrequesttypedef).

Keyword-only arguments:

- `TrafficMirrorSessionIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeTrafficMirrorSessionsResultTypeDef](./type_defs.md#describetrafficmirrorsessionsresulttypedef).

<a id="describe_traffic_mirror_targets"></a>

### describe_traffic_mirror_targets

Information about one or more Traffic Mirror targets.

Type annotations for
`aiobotocore.create_client("ec2").describe_traffic_mirror_targets` method.

Boto3 documentation:
[EC2.Client.describe_traffic_mirror_targets](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_traffic_mirror_targets)

Asynchronous method. Use `await describe_traffic_mirror_targets(...)` for a
synchronous call.

Arguments mapping described in
[DescribeTrafficMirrorTargetsRequestRequestTypeDef](./type_defs.md#describetrafficmirrortargetsrequestrequesttypedef).

Keyword-only arguments:

- `TrafficMirrorTargetIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeTrafficMirrorTargetsResultTypeDef](./type_defs.md#describetrafficmirrortargetsresulttypedef).

<a id="describe_transit_gateway_attachments"></a>

### describe_transit_gateway_attachments

Describes one or more attachments between resources and transit gateways.

Type annotations for
`aiobotocore.create_client("ec2").describe_transit_gateway_attachments` method.

Boto3 documentation:
[EC2.Client.describe_transit_gateway_attachments](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_transit_gateway_attachments)

Asynchronous method. Use `await describe_transit_gateway_attachments(...)` for
a synchronous call.

Arguments mapping described in
[DescribeTransitGatewayAttachmentsRequestRequestTypeDef](./type_defs.md#describetransitgatewayattachmentsrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayAttachmentIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeTransitGatewayAttachmentsResultTypeDef](./type_defs.md#describetransitgatewayattachmentsresulttypedef).

<a id="describe_transit_gateway_connect_peers"></a>

### describe_transit_gateway_connect_peers

Describes one or more Connect peers.

Type annotations for
`aiobotocore.create_client("ec2").describe_transit_gateway_connect_peers`
method.

Boto3 documentation:
[EC2.Client.describe_transit_gateway_connect_peers](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_transit_gateway_connect_peers)

Asynchronous method. Use `await describe_transit_gateway_connect_peers(...)`
for a synchronous call.

Arguments mapping described in
[DescribeTransitGatewayConnectPeersRequestRequestTypeDef](./type_defs.md#describetransitgatewayconnectpeersrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayConnectPeerIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeTransitGatewayConnectPeersResultTypeDef](./type_defs.md#describetransitgatewayconnectpeersresulttypedef).

<a id="describe_transit_gateway_connects"></a>

### describe_transit_gateway_connects

Describes one or more Connect attachments.

Type annotations for
`aiobotocore.create_client("ec2").describe_transit_gateway_connects` method.

Boto3 documentation:
[EC2.Client.describe_transit_gateway_connects](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_transit_gateway_connects)

Asynchronous method. Use `await describe_transit_gateway_connects(...)` for a
synchronous call.

Arguments mapping described in
[DescribeTransitGatewayConnectsRequestRequestTypeDef](./type_defs.md#describetransitgatewayconnectsrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayAttachmentIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeTransitGatewayConnectsResultTypeDef](./type_defs.md#describetransitgatewayconnectsresulttypedef).

<a id="describe_transit_gateway_multicast_domains"></a>

### describe_transit_gateway_multicast_domains

Describes one or more transit gateway multicast domains.

Type annotations for
`aiobotocore.create_client("ec2").describe_transit_gateway_multicast_domains`
method.

Boto3 documentation:
[EC2.Client.describe_transit_gateway_multicast_domains](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_transit_gateway_multicast_domains)

Asynchronous method. Use
`await describe_transit_gateway_multicast_domains(...)` for a synchronous call.

Arguments mapping described in
[DescribeTransitGatewayMulticastDomainsRequestRequestTypeDef](./type_defs.md#describetransitgatewaymulticastdomainsrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayMulticastDomainIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeTransitGatewayMulticastDomainsResultTypeDef](./type_defs.md#describetransitgatewaymulticastdomainsresulttypedef).

<a id="describe_transit_gateway_peering_attachments"></a>

### describe_transit_gateway_peering_attachments

Describes your transit gateway peering attachments.

Type annotations for
`aiobotocore.create_client("ec2").describe_transit_gateway_peering_attachments`
method.

Boto3 documentation:
[EC2.Client.describe_transit_gateway_peering_attachments](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_transit_gateway_peering_attachments)

Asynchronous method. Use
`await describe_transit_gateway_peering_attachments(...)` for a synchronous
call.

Arguments mapping described in
[DescribeTransitGatewayPeeringAttachmentsRequestRequestTypeDef](./type_defs.md#describetransitgatewaypeeringattachmentsrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayAttachmentIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeTransitGatewayPeeringAttachmentsResultTypeDef](./type_defs.md#describetransitgatewaypeeringattachmentsresulttypedef).

<a id="describe_transit_gateway_route_tables"></a>

### describe_transit_gateway_route_tables

Describes one or more transit gateway route tables.

Type annotations for
`aiobotocore.create_client("ec2").describe_transit_gateway_route_tables`
method.

Boto3 documentation:
[EC2.Client.describe_transit_gateway_route_tables](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_transit_gateway_route_tables)

Asynchronous method. Use `await describe_transit_gateway_route_tables(...)` for
a synchronous call.

Arguments mapping described in
[DescribeTransitGatewayRouteTablesRequestRequestTypeDef](./type_defs.md#describetransitgatewayroutetablesrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayRouteTableIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeTransitGatewayRouteTablesResultTypeDef](./type_defs.md#describetransitgatewayroutetablesresulttypedef).

<a id="describe_transit_gateway_vpc_attachments"></a>

### describe_transit_gateway_vpc_attachments

Describes one or more VPC attachments.

Type annotations for
`aiobotocore.create_client("ec2").describe_transit_gateway_vpc_attachments`
method.

Boto3 documentation:
[EC2.Client.describe_transit_gateway_vpc_attachments](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_transit_gateway_vpc_attachments)

Asynchronous method. Use `await describe_transit_gateway_vpc_attachments(...)`
for a synchronous call.

Arguments mapping described in
[DescribeTransitGatewayVpcAttachmentsRequestRequestTypeDef](./type_defs.md#describetransitgatewayvpcattachmentsrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayAttachmentIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeTransitGatewayVpcAttachmentsResultTypeDef](./type_defs.md#describetransitgatewayvpcattachmentsresulttypedef).

<a id="describe_transit_gateways"></a>

### describe_transit_gateways

Describes one or more transit gateways.

Type annotations for
`aiobotocore.create_client("ec2").describe_transit_gateways` method.

Boto3 documentation:
[EC2.Client.describe_transit_gateways](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_transit_gateways)

Asynchronous method. Use `await describe_transit_gateways(...)` for a
synchronous call.

Arguments mapping described in
[DescribeTransitGatewaysRequestRequestTypeDef](./type_defs.md#describetransitgatewaysrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeTransitGatewaysResultTypeDef](./type_defs.md#describetransitgatewaysresulttypedef).

<a id="describe_trunk_interface_associations"></a>

### describe_trunk_interface_associations

.

Type annotations for
`aiobotocore.create_client("ec2").describe_trunk_interface_associations`
method.

Boto3 documentation:
[EC2.Client.describe_trunk_interface_associations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_trunk_interface_associations)

Asynchronous method. Use `await describe_trunk_interface_associations(...)` for
a synchronous call.

Arguments mapping described in
[DescribeTrunkInterfaceAssociationsRequestRequestTypeDef](./type_defs.md#describetrunkinterfaceassociationsrequestrequesttypedef).

Keyword-only arguments:

- `AssociationIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[DescribeTrunkInterfaceAssociationsResultTypeDef](./type_defs.md#describetrunkinterfaceassociationsresulttypedef).

<a id="describe_volume_attribute"></a>

### describe_volume_attribute

Describes the specified attribute of the specified volume.

Type annotations for
`aiobotocore.create_client("ec2").describe_volume_attribute` method.

Boto3 documentation:
[EC2.Client.describe_volume_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_volume_attribute)

Asynchronous method. Use `await describe_volume_attribute(...)` for a
synchronous call.

Arguments mapping described in
[DescribeVolumeAttributeRequestRequestTypeDef](./type_defs.md#describevolumeattributerequestrequesttypedef).

Keyword-only arguments:

- `Attribute`: [VolumeAttributeNameType](./literals.md#volumeattributenametype)
  *(required)*
- `VolumeId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeVolumeAttributeResultTypeDef](./type_defs.md#describevolumeattributeresulttypedef).

<a id="describe_volume_status"></a>

### describe_volume_status

Describes the status of the specified volumes.

Type annotations for `aiobotocore.create_client("ec2").describe_volume_status`
method.

Boto3 documentation:
[EC2.Client.describe_volume_status](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_volume_status)

Asynchronous method. Use `await describe_volume_status(...)` for a synchronous
call.

Arguments mapping described in
[DescribeVolumeStatusRequestRequestTypeDef](./type_defs.md#describevolumestatusrequestrequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `VolumeIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeVolumeStatusResultTypeDef](./type_defs.md#describevolumestatusresulttypedef).

<a id="describe_volumes"></a>

### describe_volumes

Describes the specified EBS volumes or all of your EBS volumes.

Type annotations for `aiobotocore.create_client("ec2").describe_volumes`
method.

Boto3 documentation:
[EC2.Client.describe_volumes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_volumes)

Asynchronous method. Use `await describe_volumes(...)` for a synchronous call.

Arguments mapping described in
[DescribeVolumesRequestRequestTypeDef](./type_defs.md#describevolumesrequestrequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `VolumeIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeVolumesResultTypeDef](./type_defs.md#describevolumesresulttypedef).

<a id="describe_volumes_modifications"></a>

### describe_volumes_modifications

Describes the most recent volume modification request for the specified EBS
volumes.

Type annotations for
`aiobotocore.create_client("ec2").describe_volumes_modifications` method.

Boto3 documentation:
[EC2.Client.describe_volumes_modifications](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_volumes_modifications)

Asynchronous method. Use `await describe_volumes_modifications(...)` for a
synchronous call.

Arguments mapping described in
[DescribeVolumesModificationsRequestRequestTypeDef](./type_defs.md#describevolumesmodificationsrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `VolumeIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[DescribeVolumesModificationsResultTypeDef](./type_defs.md#describevolumesmodificationsresulttypedef).

<a id="describe_vpc_attribute"></a>

### describe_vpc_attribute

Describes the specified attribute of the specified VPC.

Type annotations for `aiobotocore.create_client("ec2").describe_vpc_attribute`
method.

Boto3 documentation:
[EC2.Client.describe_vpc_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_vpc_attribute)

Asynchronous method. Use `await describe_vpc_attribute(...)` for a synchronous
call.

Arguments mapping described in
[DescribeVpcAttributeRequestRequestTypeDef](./type_defs.md#describevpcattributerequestrequesttypedef).

Keyword-only arguments:

- `Attribute`: [VpcAttributeNameType](./literals.md#vpcattributenametype)
  *(required)*
- `VpcId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeVpcAttributeResultTypeDef](./type_defs.md#describevpcattributeresulttypedef).

<a id="describe_vpc_classic_link"></a>

### describe_vpc_classic_link

Describes the ClassicLink status of one or more VPCs.

Type annotations for
`aiobotocore.create_client("ec2").describe_vpc_classic_link` method.

Boto3 documentation:
[EC2.Client.describe_vpc_classic_link](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_vpc_classic_link)

Asynchronous method. Use `await describe_vpc_classic_link(...)` for a
synchronous call.

Arguments mapping described in
[DescribeVpcClassicLinkRequestRequestTypeDef](./type_defs.md#describevpcclassiclinkrequestrequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `VpcIds`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[DescribeVpcClassicLinkResultTypeDef](./type_defs.md#describevpcclassiclinkresulttypedef).

<a id="describe_vpc_classic_link_dns_support"></a>

### describe_vpc_classic_link_dns_support

Describes the ClassicLink DNS support status of one or more VPCs.

Type annotations for
`aiobotocore.create_client("ec2").describe_vpc_classic_link_dns_support`
method.

Boto3 documentation:
[EC2.Client.describe_vpc_classic_link_dns_support](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_vpc_classic_link_dns_support)

Asynchronous method. Use `await describe_vpc_classic_link_dns_support(...)` for
a synchronous call.

Arguments mapping described in
[DescribeVpcClassicLinkDnsSupportRequestRequestTypeDef](./type_defs.md#describevpcclassiclinkdnssupportrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`
- `VpcIds`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[DescribeVpcClassicLinkDnsSupportResultTypeDef](./type_defs.md#describevpcclassiclinkdnssupportresulttypedef).

<a id="describe_vpc_endpoint_connection_notifications"></a>

### describe_vpc_endpoint_connection_notifications

Describes the connection notifications for VPC endpoints and VPC endpoint
services.

Type annotations for
`aiobotocore.create_client("ec2").describe_vpc_endpoint_connection_notifications`
method.

Boto3 documentation:
[EC2.Client.describe_vpc_endpoint_connection_notifications](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_vpc_endpoint_connection_notifications)

Asynchronous method. Use
`await describe_vpc_endpoint_connection_notifications(...)` for a synchronous
call.

Arguments mapping described in
[DescribeVpcEndpointConnectionNotificationsRequestRequestTypeDef](./type_defs.md#describevpcendpointconnectionnotificationsrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `ConnectionNotificationId`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeVpcEndpointConnectionNotificationsResultTypeDef](./type_defs.md#describevpcendpointconnectionnotificationsresulttypedef).

<a id="describe_vpc_endpoint_connections"></a>

### describe_vpc_endpoint_connections

Describes the VPC endpoint connections to your VPC endpoint services, including
any endpoints that are pending your acceptance.

Type annotations for
`aiobotocore.create_client("ec2").describe_vpc_endpoint_connections` method.

Boto3 documentation:
[EC2.Client.describe_vpc_endpoint_connections](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_vpc_endpoint_connections)

Asynchronous method. Use `await describe_vpc_endpoint_connections(...)` for a
synchronous call.

Arguments mapping described in
[DescribeVpcEndpointConnectionsRequestRequestTypeDef](./type_defs.md#describevpcendpointconnectionsrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeVpcEndpointConnectionsResultTypeDef](./type_defs.md#describevpcendpointconnectionsresulttypedef).

<a id="describe_vpc_endpoint_service_configurations"></a>

### describe_vpc_endpoint_service_configurations

Describes the VPC endpoint service configurations in your account (your
services).

Type annotations for
`aiobotocore.create_client("ec2").describe_vpc_endpoint_service_configurations`
method.

Boto3 documentation:
[EC2.Client.describe_vpc_endpoint_service_configurations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_vpc_endpoint_service_configurations)

Asynchronous method. Use
`await describe_vpc_endpoint_service_configurations(...)` for a synchronous
call.

Arguments mapping described in
[DescribeVpcEndpointServiceConfigurationsRequestRequestTypeDef](./type_defs.md#describevpcendpointserviceconfigurationsrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `ServiceIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeVpcEndpointServiceConfigurationsResultTypeDef](./type_defs.md#describevpcendpointserviceconfigurationsresulttypedef).

<a id="describe_vpc_endpoint_service_permissions"></a>

### describe_vpc_endpoint_service_permissions

Describes the principals (service consumers) that are permitted to discover
your VPC endpoint service.

Type annotations for
`aiobotocore.create_client("ec2").describe_vpc_endpoint_service_permissions`
method.

Boto3 documentation:
[EC2.Client.describe_vpc_endpoint_service_permissions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_vpc_endpoint_service_permissions)

Asynchronous method. Use `await describe_vpc_endpoint_service_permissions(...)`
for a synchronous call.

Arguments mapping described in
[DescribeVpcEndpointServicePermissionsRequestRequestTypeDef](./type_defs.md#describevpcendpointservicepermissionsrequestrequesttypedef).

Keyword-only arguments:

- `ServiceId`: `str` *(required)*
- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeVpcEndpointServicePermissionsResultTypeDef](./type_defs.md#describevpcendpointservicepermissionsresulttypedef).

<a id="describe_vpc_endpoint_services"></a>

### describe_vpc_endpoint_services

Describes available services to which you can create a VPC endpoint.

Type annotations for
`aiobotocore.create_client("ec2").describe_vpc_endpoint_services` method.

Boto3 documentation:
[EC2.Client.describe_vpc_endpoint_services](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_vpc_endpoint_services)

Asynchronous method. Use `await describe_vpc_endpoint_services(...)` for a
synchronous call.

Arguments mapping described in
[DescribeVpcEndpointServicesRequestRequestTypeDef](./type_defs.md#describevpcendpointservicesrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `ServiceNames`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeVpcEndpointServicesResultTypeDef](./type_defs.md#describevpcendpointservicesresulttypedef).

<a id="describe_vpc_endpoints"></a>

### describe_vpc_endpoints

Describes one or more of your VPC endpoints.

Type annotations for `aiobotocore.create_client("ec2").describe_vpc_endpoints`
method.

Boto3 documentation:
[EC2.Client.describe_vpc_endpoints](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_vpc_endpoints)

Asynchronous method. Use `await describe_vpc_endpoints(...)` for a synchronous
call.

Arguments mapping described in
[DescribeVpcEndpointsRequestRequestTypeDef](./type_defs.md#describevpcendpointsrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `VpcEndpointIds`: `Sequence`\[`str`\]
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[DescribeVpcEndpointsResultTypeDef](./type_defs.md#describevpcendpointsresulttypedef).

<a id="describe_vpc_peering_connections"></a>

### describe_vpc_peering_connections

Describes one or more of your VPC peering connections.

Type annotations for
`aiobotocore.create_client("ec2").describe_vpc_peering_connections` method.

Boto3 documentation:
[EC2.Client.describe_vpc_peering_connections](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_vpc_peering_connections)

Asynchronous method. Use `await describe_vpc_peering_connections(...)` for a
synchronous call.

Arguments mapping described in
[DescribeVpcPeeringConnectionsRequestRequestTypeDef](./type_defs.md#describevpcpeeringconnectionsrequestrequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `VpcPeeringConnectionIds`: `Sequence`\[`str`\]
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[DescribeVpcPeeringConnectionsResultTypeDef](./type_defs.md#describevpcpeeringconnectionsresulttypedef).

<a id="describe_vpcs"></a>

### describe_vpcs

Describes one or more of your VPCs.

Type annotations for `aiobotocore.create_client("ec2").describe_vpcs` method.

Boto3 documentation:
[EC2.Client.describe_vpcs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_vpcs)

Asynchronous method. Use `await describe_vpcs(...)` for a synchronous call.

Arguments mapping described in
[DescribeVpcsRequestRequestTypeDef](./type_defs.md#describevpcsrequestrequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `VpcIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[DescribeVpcsResultTypeDef](./type_defs.md#describevpcsresulttypedef).

<a id="describe_vpn_connections"></a>

### describe_vpn_connections

Describes one or more of your VPN connections.

Type annotations for
`aiobotocore.create_client("ec2").describe_vpn_connections` method.

Boto3 documentation:
[EC2.Client.describe_vpn_connections](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_vpn_connections)

Asynchronous method. Use `await describe_vpn_connections(...)` for a
synchronous call.

Arguments mapping described in
[DescribeVpnConnectionsRequestRequestTypeDef](./type_defs.md#describevpnconnectionsrequestrequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `VpnConnectionIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeVpnConnectionsResultTypeDef](./type_defs.md#describevpnconnectionsresulttypedef).

<a id="describe_vpn_gateways"></a>

### describe_vpn_gateways

Describes one or more of your virtual private gateways.

Type annotations for `aiobotocore.create_client("ec2").describe_vpn_gateways`
method.

Boto3 documentation:
[EC2.Client.describe_vpn_gateways](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.describe_vpn_gateways)

Asynchronous method. Use `await describe_vpn_gateways(...)` for a synchronous
call.

Arguments mapping described in
[DescribeVpnGatewaysRequestRequestTypeDef](./type_defs.md#describevpngatewaysrequestrequesttypedef).

Keyword-only arguments:

- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `VpnGatewayIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[DescribeVpnGatewaysResultTypeDef](./type_defs.md#describevpngatewaysresulttypedef).

<a id="detach_classic_link_vpc"></a>

### detach_classic_link_vpc

Unlinks (detaches) a linked EC2-Classic instance from a VPC.

Type annotations for `aiobotocore.create_client("ec2").detach_classic_link_vpc`
method.

Boto3 documentation:
[EC2.Client.detach_classic_link_vpc](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.detach_classic_link_vpc)

Asynchronous method. Use `await detach_classic_link_vpc(...)` for a synchronous
call.

Arguments mapping described in
[DetachClassicLinkVpcRequestRequestTypeDef](./type_defs.md#detachclassiclinkvpcrequestrequesttypedef).

Keyword-only arguments:

- `InstanceId`: `str` *(required)*
- `VpcId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DetachClassicLinkVpcResultTypeDef](./type_defs.md#detachclassiclinkvpcresulttypedef).

<a id="detach_internet_gateway"></a>

### detach_internet_gateway

Detaches an internet gateway from a VPC, disabling connectivity between the
internet and the VPC.

Type annotations for `aiobotocore.create_client("ec2").detach_internet_gateway`
method.

Boto3 documentation:
[EC2.Client.detach_internet_gateway](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.detach_internet_gateway)

Asynchronous method. Use `await detach_internet_gateway(...)` for a synchronous
call.

Arguments mapping described in
[DetachInternetGatewayRequestRequestTypeDef](./type_defs.md#detachinternetgatewayrequestrequesttypedef).

Keyword-only arguments:

- `InternetGatewayId`: `str` *(required)*
- `VpcId`: `str` *(required)*
- `DryRun`: `bool`

<a id="detach_network_interface"></a>

### detach_network_interface

Detaches a network interface from an instance.

Type annotations for
`aiobotocore.create_client("ec2").detach_network_interface` method.

Boto3 documentation:
[EC2.Client.detach_network_interface](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.detach_network_interface)

Asynchronous method. Use `await detach_network_interface(...)` for a
synchronous call.

Arguments mapping described in
[DetachNetworkInterfaceRequestRequestTypeDef](./type_defs.md#detachnetworkinterfacerequestrequesttypedef).

Keyword-only arguments:

- `AttachmentId`: `str` *(required)*
- `DryRun`: `bool`
- `Force`: `bool`

<a id="detach_volume"></a>

### detach_volume

Detaches an EBS volume from an instance.

Type annotations for `aiobotocore.create_client("ec2").detach_volume` method.

Boto3 documentation:
[EC2.Client.detach_volume](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.detach_volume)

Asynchronous method. Use `await detach_volume(...)` for a synchronous call.

Arguments mapping described in
[DetachVolumeRequestRequestTypeDef](./type_defs.md#detachvolumerequestrequesttypedef).

Keyword-only arguments:

- `VolumeId`: `str` *(required)*
- `Device`: `str`
- `Force`: `bool`
- `InstanceId`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[VolumeAttachmentResponseMetadataTypeDef](./type_defs.md#volumeattachmentresponsemetadatatypedef).

<a id="detach_vpn_gateway"></a>

### detach_vpn_gateway

Detaches a virtual private gateway from a VPC.

Type annotations for `aiobotocore.create_client("ec2").detach_vpn_gateway`
method.

Boto3 documentation:
[EC2.Client.detach_vpn_gateway](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.detach_vpn_gateway)

Asynchronous method. Use `await detach_vpn_gateway(...)` for a synchronous
call.

Arguments mapping described in
[DetachVpnGatewayRequestRequestTypeDef](./type_defs.md#detachvpngatewayrequestrequesttypedef).

Keyword-only arguments:

- `VpcId`: `str` *(required)*
- `VpnGatewayId`: `str` *(required)*
- `DryRun`: `bool`

<a id="disable_ebs_encryption_by_default"></a>

### disable_ebs_encryption_by_default

Disables EBS encryption by default for your account in the current Region.

Type annotations for
`aiobotocore.create_client("ec2").disable_ebs_encryption_by_default` method.

Boto3 documentation:
[EC2.Client.disable_ebs_encryption_by_default](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.disable_ebs_encryption_by_default)

Asynchronous method. Use `await disable_ebs_encryption_by_default(...)` for a
synchronous call.

Arguments mapping described in
[DisableEbsEncryptionByDefaultRequestRequestTypeDef](./type_defs.md#disableebsencryptionbydefaultrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`

Returns a `Coroutine` for
[DisableEbsEncryptionByDefaultResultTypeDef](./type_defs.md#disableebsencryptionbydefaultresulttypedef).

<a id="disable_fast_snapshot_restores"></a>

### disable_fast_snapshot_restores

Disables fast snapshot restores for the specified snapshots in the specified
Availability Zones.

Type annotations for
`aiobotocore.create_client("ec2").disable_fast_snapshot_restores` method.

Boto3 documentation:
[EC2.Client.disable_fast_snapshot_restores](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.disable_fast_snapshot_restores)

Asynchronous method. Use `await disable_fast_snapshot_restores(...)` for a
synchronous call.

Arguments mapping described in
[DisableFastSnapshotRestoresRequestRequestTypeDef](./type_defs.md#disablefastsnapshotrestoresrequestrequesttypedef).

Keyword-only arguments:

- `AvailabilityZones`: `Sequence`\[`str`\] *(required)*
- `SourceSnapshotIds`: `Sequence`\[`str`\] *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DisableFastSnapshotRestoresResultTypeDef](./type_defs.md#disablefastsnapshotrestoresresulttypedef).

<a id="disable_image_deprecation"></a>

### disable_image_deprecation

Cancels the deprecation of the specified AMI.

Type annotations for
`aiobotocore.create_client("ec2").disable_image_deprecation` method.

Boto3 documentation:
[EC2.Client.disable_image_deprecation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.disable_image_deprecation)

Asynchronous method. Use `await disable_image_deprecation(...)` for a
synchronous call.

Arguments mapping described in
[DisableImageDeprecationRequestRequestTypeDef](./type_defs.md#disableimagedeprecationrequestrequesttypedef).

Keyword-only arguments:

- `ImageId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DisableImageDeprecationResultTypeDef](./type_defs.md#disableimagedeprecationresulttypedef).

<a id="disable_ipam_organization_admin_account"></a>

### disable_ipam_organization_admin_account

Disable the IPAM account.

Type annotations for
`aiobotocore.create_client("ec2").disable_ipam_organization_admin_account`
method.

Boto3 documentation:
[EC2.Client.disable_ipam_organization_admin_account](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.disable_ipam_organization_admin_account)

Asynchronous method. Use `await disable_ipam_organization_admin_account(...)`
for a synchronous call.

Arguments mapping described in
[DisableIpamOrganizationAdminAccountRequestRequestTypeDef](./type_defs.md#disableipamorganizationadminaccountrequestrequesttypedef).

Keyword-only arguments:

- `DelegatedAdminAccountId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DisableIpamOrganizationAdminAccountResultTypeDef](./type_defs.md#disableipamorganizationadminaccountresulttypedef).

<a id="disable_serial_console_access"></a>

### disable_serial_console_access

Disables access to the EC2 serial console of all instances for your account.

Type annotations for
`aiobotocore.create_client("ec2").disable_serial_console_access` method.

Boto3 documentation:
[EC2.Client.disable_serial_console_access](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.disable_serial_console_access)

Asynchronous method. Use `await disable_serial_console_access(...)` for a
synchronous call.

Arguments mapping described in
[DisableSerialConsoleAccessRequestRequestTypeDef](./type_defs.md#disableserialconsoleaccessrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`

Returns a `Coroutine` for
[DisableSerialConsoleAccessResultTypeDef](./type_defs.md#disableserialconsoleaccessresulttypedef).

<a id="disable_transit_gateway_route_table_propagation"></a>

### disable_transit_gateway_route_table_propagation

Disables the specified resource attachment from propagating routes to the
specified propagation route table.

Type annotations for
`aiobotocore.create_client("ec2").disable_transit_gateway_route_table_propagation`
method.

Boto3 documentation:
[EC2.Client.disable_transit_gateway_route_table_propagation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.disable_transit_gateway_route_table_propagation)

Asynchronous method. Use
`await disable_transit_gateway_route_table_propagation(...)` for a synchronous
call.

Arguments mapping described in
[DisableTransitGatewayRouteTablePropagationRequestRequestTypeDef](./type_defs.md#disabletransitgatewayroutetablepropagationrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayRouteTableId`: `str` *(required)*
- `TransitGatewayAttachmentId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DisableTransitGatewayRouteTablePropagationResultTypeDef](./type_defs.md#disabletransitgatewayroutetablepropagationresulttypedef).

<a id="disable_vgw_route_propagation"></a>

### disable_vgw_route_propagation

Disables a virtual private gateway (VGW) from propagating routes to a specified
route table of a VPC.

Type annotations for
`aiobotocore.create_client("ec2").disable_vgw_route_propagation` method.

Boto3 documentation:
[EC2.Client.disable_vgw_route_propagation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.disable_vgw_route_propagation)

Asynchronous method. Use `await disable_vgw_route_propagation(...)` for a
synchronous call.

Arguments mapping described in
[DisableVgwRoutePropagationRequestRequestTypeDef](./type_defs.md#disablevgwroutepropagationrequestrequesttypedef).

Keyword-only arguments:

- `GatewayId`: `str` *(required)*
- `RouteTableId`: `str` *(required)*
- `DryRun`: `bool`

<a id="disable_vpc_classic_link"></a>

### disable_vpc_classic_link

Disables ClassicLink for a VPC.

Type annotations for
`aiobotocore.create_client("ec2").disable_vpc_classic_link` method.

Boto3 documentation:
[EC2.Client.disable_vpc_classic_link](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.disable_vpc_classic_link)

Asynchronous method. Use `await disable_vpc_classic_link(...)` for a
synchronous call.

Arguments mapping described in
[DisableVpcClassicLinkRequestRequestTypeDef](./type_defs.md#disablevpcclassiclinkrequestrequesttypedef).

Keyword-only arguments:

- `VpcId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DisableVpcClassicLinkResultTypeDef](./type_defs.md#disablevpcclassiclinkresulttypedef).

<a id="disable_vpc_classic_link_dns_support"></a>

### disable_vpc_classic_link_dns_support

Disables ClassicLink DNS support for a VPC.

Type annotations for
`aiobotocore.create_client("ec2").disable_vpc_classic_link_dns_support` method.

Boto3 documentation:
[EC2.Client.disable_vpc_classic_link_dns_support](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.disable_vpc_classic_link_dns_support)

Asynchronous method. Use `await disable_vpc_classic_link_dns_support(...)` for
a synchronous call.

Arguments mapping described in
[DisableVpcClassicLinkDnsSupportRequestRequestTypeDef](./type_defs.md#disablevpcclassiclinkdnssupportrequestrequesttypedef).

Keyword-only arguments:

- `VpcId`: `str`

Returns a `Coroutine` for
[DisableVpcClassicLinkDnsSupportResultTypeDef](./type_defs.md#disablevpcclassiclinkdnssupportresulttypedef).

<a id="disassociate_address"></a>

### disassociate_address

Disassociates an Elastic IP address from the instance or network interface it's
associated with.

Type annotations for `aiobotocore.create_client("ec2").disassociate_address`
method.

Boto3 documentation:
[EC2.Client.disassociate_address](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.disassociate_address)

Asynchronous method. Use `await disassociate_address(...)` for a synchronous
call.

Arguments mapping described in
[DisassociateAddressRequestRequestTypeDef](./type_defs.md#disassociateaddressrequestrequesttypedef).

Keyword-only arguments:

- `AssociationId`: `str`
- `PublicIp`: `str`
- `DryRun`: `bool`

<a id="disassociate_client_vpn_target_network"></a>

### disassociate_client_vpn_target_network

Disassociates a target network from the specified Client VPN endpoint.

Type annotations for
`aiobotocore.create_client("ec2").disassociate_client_vpn_target_network`
method.

Boto3 documentation:
[EC2.Client.disassociate_client_vpn_target_network](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.disassociate_client_vpn_target_network)

Asynchronous method. Use `await disassociate_client_vpn_target_network(...)`
for a synchronous call.

Arguments mapping described in
[DisassociateClientVpnTargetNetworkRequestRequestTypeDef](./type_defs.md#disassociateclientvpntargetnetworkrequestrequesttypedef).

Keyword-only arguments:

- `ClientVpnEndpointId`: `str` *(required)*
- `AssociationId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DisassociateClientVpnTargetNetworkResultTypeDef](./type_defs.md#disassociateclientvpntargetnetworkresulttypedef).

<a id="disassociate_enclave_certificate_iam_role"></a>

### disassociate_enclave_certificate_iam_role

Disassociates an IAM role from an Certificate Manager (ACM) certificate.

Type annotations for
`aiobotocore.create_client("ec2").disassociate_enclave_certificate_iam_role`
method.

Boto3 documentation:
[EC2.Client.disassociate_enclave_certificate_iam_role](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.disassociate_enclave_certificate_iam_role)

Asynchronous method. Use `await disassociate_enclave_certificate_iam_role(...)`
for a synchronous call.

Arguments mapping described in
[DisassociateEnclaveCertificateIamRoleRequestRequestTypeDef](./type_defs.md#disassociateenclavecertificateiamrolerequestrequesttypedef).

Keyword-only arguments:

- `CertificateArn`: `str`
- `RoleArn`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[DisassociateEnclaveCertificateIamRoleResultTypeDef](./type_defs.md#disassociateenclavecertificateiamroleresulttypedef).

<a id="disassociate_iam_instance_profile"></a>

### disassociate_iam_instance_profile

Disassociates an IAM instance profile from a running or stopped instance.

Type annotations for
`aiobotocore.create_client("ec2").disassociate_iam_instance_profile` method.

Boto3 documentation:
[EC2.Client.disassociate_iam_instance_profile](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.disassociate_iam_instance_profile)

Asynchronous method. Use `await disassociate_iam_instance_profile(...)` for a
synchronous call.

Arguments mapping described in
[DisassociateIamInstanceProfileRequestRequestTypeDef](./type_defs.md#disassociateiaminstanceprofilerequestrequesttypedef).

Keyword-only arguments:

- `AssociationId`: `str` *(required)*

Returns a `Coroutine` for
[DisassociateIamInstanceProfileResultTypeDef](./type_defs.md#disassociateiaminstanceprofileresulttypedef).

<a id="disassociate_instance_event_window"></a>

### disassociate_instance_event_window

Disassociates one or more targets from an event window.

Type annotations for
`aiobotocore.create_client("ec2").disassociate_instance_event_window` method.

Boto3 documentation:
[EC2.Client.disassociate_instance_event_window](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.disassociate_instance_event_window)

Asynchronous method. Use `await disassociate_instance_event_window(...)` for a
synchronous call.

Arguments mapping described in
[DisassociateInstanceEventWindowRequestRequestTypeDef](./type_defs.md#disassociateinstanceeventwindowrequestrequesttypedef).

Keyword-only arguments:

- `InstanceEventWindowId`: `str` *(required)*
- `AssociationTarget`:
  [InstanceEventWindowDisassociationRequestTypeDef](./type_defs.md#instanceeventwindowdisassociationrequesttypedef)
  *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DisassociateInstanceEventWindowResultTypeDef](./type_defs.md#disassociateinstanceeventwindowresulttypedef).

<a id="disassociate_route_table"></a>

### disassociate_route_table

Disassociates a subnet or gateway from a route table.

Type annotations for
`aiobotocore.create_client("ec2").disassociate_route_table` method.

Boto3 documentation:
[EC2.Client.disassociate_route_table](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.disassociate_route_table)

Asynchronous method. Use `await disassociate_route_table(...)` for a
synchronous call.

Arguments mapping described in
[DisassociateRouteTableRequestRequestTypeDef](./type_defs.md#disassociateroutetablerequestrequesttypedef).

Keyword-only arguments:

- `AssociationId`: `str` *(required)*
- `DryRun`: `bool`

<a id="disassociate_subnet_cidr_block"></a>

### disassociate_subnet_cidr_block

Disassociates a CIDR block from a subnet.

Type annotations for
`aiobotocore.create_client("ec2").disassociate_subnet_cidr_block` method.

Boto3 documentation:
[EC2.Client.disassociate_subnet_cidr_block](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.disassociate_subnet_cidr_block)

Asynchronous method. Use `await disassociate_subnet_cidr_block(...)` for a
synchronous call.

Arguments mapping described in
[DisassociateSubnetCidrBlockRequestRequestTypeDef](./type_defs.md#disassociatesubnetcidrblockrequestrequesttypedef).

Keyword-only arguments:

- `AssociationId`: `str` *(required)*

Returns a `Coroutine` for
[DisassociateSubnetCidrBlockResultTypeDef](./type_defs.md#disassociatesubnetcidrblockresulttypedef).

<a id="disassociate_transit_gateway_multicast_domain"></a>

### disassociate_transit_gateway_multicast_domain

Disassociates the specified subnets from the transit gateway multicast domain.

Type annotations for
`aiobotocore.create_client("ec2").disassociate_transit_gateway_multicast_domain`
method.

Boto3 documentation:
[EC2.Client.disassociate_transit_gateway_multicast_domain](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.disassociate_transit_gateway_multicast_domain)

Asynchronous method. Use
`await disassociate_transit_gateway_multicast_domain(...)` for a synchronous
call.

Arguments mapping described in
[DisassociateTransitGatewayMulticastDomainRequestRequestTypeDef](./type_defs.md#disassociatetransitgatewaymulticastdomainrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayMulticastDomainId`: `str`
- `TransitGatewayAttachmentId`: `str`
- `SubnetIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[DisassociateTransitGatewayMulticastDomainResultTypeDef](./type_defs.md#disassociatetransitgatewaymulticastdomainresulttypedef).

<a id="disassociate_transit_gateway_route_table"></a>

### disassociate_transit_gateway_route_table

Disassociates a resource attachment from a transit gateway route table.

Type annotations for
`aiobotocore.create_client("ec2").disassociate_transit_gateway_route_table`
method.

Boto3 documentation:
[EC2.Client.disassociate_transit_gateway_route_table](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.disassociate_transit_gateway_route_table)

Asynchronous method. Use `await disassociate_transit_gateway_route_table(...)`
for a synchronous call.

Arguments mapping described in
[DisassociateTransitGatewayRouteTableRequestRequestTypeDef](./type_defs.md#disassociatetransitgatewayroutetablerequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayRouteTableId`: `str` *(required)*
- `TransitGatewayAttachmentId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[DisassociateTransitGatewayRouteTableResultTypeDef](./type_defs.md#disassociatetransitgatewayroutetableresulttypedef).

<a id="disassociate_trunk_interface"></a>

### disassociate_trunk_interface

.

Type annotations for
`aiobotocore.create_client("ec2").disassociate_trunk_interface` method.

Boto3 documentation:
[EC2.Client.disassociate_trunk_interface](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.disassociate_trunk_interface)

Asynchronous method. Use `await disassociate_trunk_interface(...)` for a
synchronous call.

Arguments mapping described in
[DisassociateTrunkInterfaceRequestRequestTypeDef](./type_defs.md#disassociatetrunkinterfacerequestrequesttypedef).

Keyword-only arguments:

- `AssociationId`: `str` *(required)*
- `ClientToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[DisassociateTrunkInterfaceResultTypeDef](./type_defs.md#disassociatetrunkinterfaceresulttypedef).

<a id="disassociate_vpc_cidr_block"></a>

### disassociate_vpc_cidr_block

Disassociates a CIDR block from a VPC.

Type annotations for
`aiobotocore.create_client("ec2").disassociate_vpc_cidr_block` method.

Boto3 documentation:
[EC2.Client.disassociate_vpc_cidr_block](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.disassociate_vpc_cidr_block)

Asynchronous method. Use `await disassociate_vpc_cidr_block(...)` for a
synchronous call.

Arguments mapping described in
[DisassociateVpcCidrBlockRequestRequestTypeDef](./type_defs.md#disassociatevpccidrblockrequestrequesttypedef).

Keyword-only arguments:

- `AssociationId`: `str` *(required)*

Returns a `Coroutine` for
[DisassociateVpcCidrBlockResultTypeDef](./type_defs.md#disassociatevpccidrblockresulttypedef).

<a id="enable_ebs_encryption_by_default"></a>

### enable_ebs_encryption_by_default

Enables EBS encryption by default for your account in the current Region.

Type annotations for
`aiobotocore.create_client("ec2").enable_ebs_encryption_by_default` method.

Boto3 documentation:
[EC2.Client.enable_ebs_encryption_by_default](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.enable_ebs_encryption_by_default)

Asynchronous method. Use `await enable_ebs_encryption_by_default(...)` for a
synchronous call.

Arguments mapping described in
[EnableEbsEncryptionByDefaultRequestRequestTypeDef](./type_defs.md#enableebsencryptionbydefaultrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`

Returns a `Coroutine` for
[EnableEbsEncryptionByDefaultResultTypeDef](./type_defs.md#enableebsencryptionbydefaultresulttypedef).

<a id="enable_fast_snapshot_restores"></a>

### enable_fast_snapshot_restores

Enables fast snapshot restores for the specified snapshots in the specified
Availability Zones.

Type annotations for
`aiobotocore.create_client("ec2").enable_fast_snapshot_restores` method.

Boto3 documentation:
[EC2.Client.enable_fast_snapshot_restores](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.enable_fast_snapshot_restores)

Asynchronous method. Use `await enable_fast_snapshot_restores(...)` for a
synchronous call.

Arguments mapping described in
[EnableFastSnapshotRestoresRequestRequestTypeDef](./type_defs.md#enablefastsnapshotrestoresrequestrequesttypedef).

Keyword-only arguments:

- `AvailabilityZones`: `Sequence`\[`str`\] *(required)*
- `SourceSnapshotIds`: `Sequence`\[`str`\] *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[EnableFastSnapshotRestoresResultTypeDef](./type_defs.md#enablefastsnapshotrestoresresulttypedef).

<a id="enable_image_deprecation"></a>

### enable_image_deprecation

Enables deprecation of the specified AMI at the specified date and time.

Type annotations for
`aiobotocore.create_client("ec2").enable_image_deprecation` method.

Boto3 documentation:
[EC2.Client.enable_image_deprecation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.enable_image_deprecation)

Asynchronous method. Use `await enable_image_deprecation(...)` for a
synchronous call.

Arguments mapping described in
[EnableImageDeprecationRequestRequestTypeDef](./type_defs.md#enableimagedeprecationrequestrequesttypedef).

Keyword-only arguments:

- `ImageId`: `str` *(required)*
- `DeprecateAt`: `Union`\[`datetime`, `str`\] *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[EnableImageDeprecationResultTypeDef](./type_defs.md#enableimagedeprecationresulttypedef).

<a id="enable_ipam_organization_admin_account"></a>

### enable_ipam_organization_admin_account

Enable an Organizations member account as the IPAM admin account.

Type annotations for
`aiobotocore.create_client("ec2").enable_ipam_organization_admin_account`
method.

Boto3 documentation:
[EC2.Client.enable_ipam_organization_admin_account](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.enable_ipam_organization_admin_account)

Asynchronous method. Use `await enable_ipam_organization_admin_account(...)`
for a synchronous call.

Arguments mapping described in
[EnableIpamOrganizationAdminAccountRequestRequestTypeDef](./type_defs.md#enableipamorganizationadminaccountrequestrequesttypedef).

Keyword-only arguments:

- `DelegatedAdminAccountId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[EnableIpamOrganizationAdminAccountResultTypeDef](./type_defs.md#enableipamorganizationadminaccountresulttypedef).

<a id="enable_serial_console_access"></a>

### enable_serial_console_access

Enables access to the EC2 serial console of all instances for your account.

Type annotations for
`aiobotocore.create_client("ec2").enable_serial_console_access` method.

Boto3 documentation:
[EC2.Client.enable_serial_console_access](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.enable_serial_console_access)

Asynchronous method. Use `await enable_serial_console_access(...)` for a
synchronous call.

Arguments mapping described in
[EnableSerialConsoleAccessRequestRequestTypeDef](./type_defs.md#enableserialconsoleaccessrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`

Returns a `Coroutine` for
[EnableSerialConsoleAccessResultTypeDef](./type_defs.md#enableserialconsoleaccessresulttypedef).

<a id="enable_transit_gateway_route_table_propagation"></a>

### enable_transit_gateway_route_table_propagation

Enables the specified attachment to propagate routes to the specified
propagation route table.

Type annotations for
`aiobotocore.create_client("ec2").enable_transit_gateway_route_table_propagation`
method.

Boto3 documentation:
[EC2.Client.enable_transit_gateway_route_table_propagation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.enable_transit_gateway_route_table_propagation)

Asynchronous method. Use
`await enable_transit_gateway_route_table_propagation(...)` for a synchronous
call.

Arguments mapping described in
[EnableTransitGatewayRouteTablePropagationRequestRequestTypeDef](./type_defs.md#enabletransitgatewayroutetablepropagationrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayRouteTableId`: `str` *(required)*
- `TransitGatewayAttachmentId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[EnableTransitGatewayRouteTablePropagationResultTypeDef](./type_defs.md#enabletransitgatewayroutetablepropagationresulttypedef).

<a id="enable_vgw_route_propagation"></a>

### enable_vgw_route_propagation

Enables a virtual private gateway (VGW) to propagate routes to the specified
route table of a VPC.

Type annotations for
`aiobotocore.create_client("ec2").enable_vgw_route_propagation` method.

Boto3 documentation:
[EC2.Client.enable_vgw_route_propagation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.enable_vgw_route_propagation)

Asynchronous method. Use `await enable_vgw_route_propagation(...)` for a
synchronous call.

Arguments mapping described in
[EnableVgwRoutePropagationRequestRequestTypeDef](./type_defs.md#enablevgwroutepropagationrequestrequesttypedef).

Keyword-only arguments:

- `GatewayId`: `str` *(required)*
- `RouteTableId`: `str` *(required)*
- `DryRun`: `bool`

<a id="enable_volume_io"></a>

### enable_volume_io

Enables I/O operations for a volume that had I/O operations disabled because
the data on the volume was potentially inconsistent.

Type annotations for `aiobotocore.create_client("ec2").enable_volume_io`
method.

Boto3 documentation:
[EC2.Client.enable_volume_io](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.enable_volume_io)

Asynchronous method. Use `await enable_volume_io(...)` for a synchronous call.

Arguments mapping described in
[EnableVolumeIORequestRequestTypeDef](./type_defs.md#enablevolumeiorequestrequesttypedef).

Keyword-only arguments:

- `VolumeId`: `str` *(required)*
- `DryRun`: `bool`

<a id="enable_vpc_classic_link"></a>

### enable_vpc_classic_link

Enables a VPC for ClassicLink.

Type annotations for `aiobotocore.create_client("ec2").enable_vpc_classic_link`
method.

Boto3 documentation:
[EC2.Client.enable_vpc_classic_link](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.enable_vpc_classic_link)

Asynchronous method. Use `await enable_vpc_classic_link(...)` for a synchronous
call.

Arguments mapping described in
[EnableVpcClassicLinkRequestRequestTypeDef](./type_defs.md#enablevpcclassiclinkrequestrequesttypedef).

Keyword-only arguments:

- `VpcId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[EnableVpcClassicLinkResultTypeDef](./type_defs.md#enablevpcclassiclinkresulttypedef).

<a id="enable_vpc_classic_link_dns_support"></a>

### enable_vpc_classic_link_dns_support

Enables a VPC to support DNS hostname resolution for ClassicLink.

Type annotations for
`aiobotocore.create_client("ec2").enable_vpc_classic_link_dns_support` method.

Boto3 documentation:
[EC2.Client.enable_vpc_classic_link_dns_support](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.enable_vpc_classic_link_dns_support)

Asynchronous method. Use `await enable_vpc_classic_link_dns_support(...)` for a
synchronous call.

Arguments mapping described in
[EnableVpcClassicLinkDnsSupportRequestRequestTypeDef](./type_defs.md#enablevpcclassiclinkdnssupportrequestrequesttypedef).

Keyword-only arguments:

- `VpcId`: `str`

Returns a `Coroutine` for
[EnableVpcClassicLinkDnsSupportResultTypeDef](./type_defs.md#enablevpcclassiclinkdnssupportresulttypedef).

<a id="export_client_vpn_client_certificate_revocation_list"></a>

### export_client_vpn_client_certificate_revocation_list

Downloads the client certificate revocation list for the specified Client VPN
endpoint.

Type annotations for
`aiobotocore.create_client("ec2").export_client_vpn_client_certificate_revocation_list`
method.

Boto3 documentation:
[EC2.Client.export_client_vpn_client_certificate_revocation_list](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.export_client_vpn_client_certificate_revocation_list)

Asynchronous method. Use
`await export_client_vpn_client_certificate_revocation_list(...)` for a
synchronous call.

Arguments mapping described in
[ExportClientVpnClientCertificateRevocationListRequestRequestTypeDef](./type_defs.md#exportclientvpnclientcertificaterevocationlistrequestrequesttypedef).

Keyword-only arguments:

- `ClientVpnEndpointId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[ExportClientVpnClientCertificateRevocationListResultTypeDef](./type_defs.md#exportclientvpnclientcertificaterevocationlistresulttypedef).

<a id="export_client_vpn_client_configuration"></a>

### export_client_vpn_client_configuration

Downloads the contents of the Client VPN endpoint configuration file for the
specified Client VPN endpoint.

Type annotations for
`aiobotocore.create_client("ec2").export_client_vpn_client_configuration`
method.

Boto3 documentation:
[EC2.Client.export_client_vpn_client_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.export_client_vpn_client_configuration)

Asynchronous method. Use `await export_client_vpn_client_configuration(...)`
for a synchronous call.

Arguments mapping described in
[ExportClientVpnClientConfigurationRequestRequestTypeDef](./type_defs.md#exportclientvpnclientconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `ClientVpnEndpointId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[ExportClientVpnClientConfigurationResultTypeDef](./type_defs.md#exportclientvpnclientconfigurationresulttypedef).

<a id="export_image"></a>

### export_image

Exports an Amazon Machine Image (AMI) to a VM file.

Type annotations for `aiobotocore.create_client("ec2").export_image` method.

Boto3 documentation:
[EC2.Client.export_image](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.export_image)

Asynchronous method. Use `await export_image(...)` for a synchronous call.

Arguments mapping described in
[ExportImageRequestRequestTypeDef](./type_defs.md#exportimagerequestrequesttypedef).

Keyword-only arguments:

- `DiskImageFormat`: [DiskImageFormatType](./literals.md#diskimageformattype)
  *(required)*
- `ImageId`: `str` *(required)*
- `S3ExportLocation`:
  [ExportTaskS3LocationRequestTypeDef](./type_defs.md#exporttasks3locationrequesttypedef)
  *(required)*
- `ClientToken`: `str`
- `Description`: `str`
- `DryRun`: `bool`
- `RoleName`: `str`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for
[ExportImageResultTypeDef](./type_defs.md#exportimageresulttypedef).

<a id="export_transit_gateway_routes"></a>

### export_transit_gateway_routes

Exports routes from the specified transit gateway route table to the specified
S3 bucket.

Type annotations for
`aiobotocore.create_client("ec2").export_transit_gateway_routes` method.

Boto3 documentation:
[EC2.Client.export_transit_gateway_routes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.export_transit_gateway_routes)

Asynchronous method. Use `await export_transit_gateway_routes(...)` for a
synchronous call.

Arguments mapping described in
[ExportTransitGatewayRoutesRequestRequestTypeDef](./type_defs.md#exporttransitgatewayroutesrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayRouteTableId`: `str` *(required)*
- `S3Bucket`: `str` *(required)*
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[ExportTransitGatewayRoutesResultTypeDef](./type_defs.md#exporttransitgatewayroutesresulttypedef).

<a id="generate_presigned_url"></a>

### generate_presigned_url

Generate a presigned url given a client, its method, and arguments.

Type annotations for `aiobotocore.create_client("ec2").generate_presigned_url`
method.

Boto3 documentation:
[EC2.Client.generate_presigned_url](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.generate_presigned_url)

Asynchronous method. Use `await generate_presigned_url(...)` for a synchronous
call.

Arguments:

- `ClientMethod`: `str` *(required)*
- `Params`: `Mapping`\[`str`, `Any`\]
- `ExpiresIn`: `int`
- `HttpMethod`: `str`

Returns a `Coroutine` for `str`.

<a id="get_associated_enclave_certificate_iam_roles"></a>

### get_associated_enclave_certificate_iam_roles

Returns the IAM roles that are associated with the specified ACM (ACM)
certificate.

Type annotations for
`aiobotocore.create_client("ec2").get_associated_enclave_certificate_iam_roles`
method.

Boto3 documentation:
[EC2.Client.get_associated_enclave_certificate_iam_roles](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.get_associated_enclave_certificate_iam_roles)

Asynchronous method. Use
`await get_associated_enclave_certificate_iam_roles(...)` for a synchronous
call.

Arguments mapping described in
[GetAssociatedEnclaveCertificateIamRolesRequestRequestTypeDef](./type_defs.md#getassociatedenclavecertificateiamrolesrequestrequesttypedef).

Keyword-only arguments:

- `CertificateArn`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[GetAssociatedEnclaveCertificateIamRolesResultTypeDef](./type_defs.md#getassociatedenclavecertificateiamrolesresulttypedef).

<a id="get_associated_ipv6_pool_cidrs"></a>

### get_associated_ipv6_pool_cidrs

Gets information about the IPv6 CIDR block associations for a specified IPv6
address pool.

Type annotations for
`aiobotocore.create_client("ec2").get_associated_ipv6_pool_cidrs` method.

Boto3 documentation:
[EC2.Client.get_associated_ipv6_pool_cidrs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.get_associated_ipv6_pool_cidrs)

Asynchronous method. Use `await get_associated_ipv6_pool_cidrs(...)` for a
synchronous call.

Arguments mapping described in
[GetAssociatedIpv6PoolCidrsRequestRequestTypeDef](./type_defs.md#getassociatedipv6poolcidrsrequestrequesttypedef).

Keyword-only arguments:

- `PoolId`: `str` *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`
- `DryRun`: `bool`

Returns a `Coroutine` for
[GetAssociatedIpv6PoolCidrsResultTypeDef](./type_defs.md#getassociatedipv6poolcidrsresulttypedef).

<a id="get_capacity_reservation_usage"></a>

### get_capacity_reservation_usage

Gets usage information about a Capacity Reservation.

Type annotations for
`aiobotocore.create_client("ec2").get_capacity_reservation_usage` method.

Boto3 documentation:
[EC2.Client.get_capacity_reservation_usage](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.get_capacity_reservation_usage)

Asynchronous method. Use `await get_capacity_reservation_usage(...)` for a
synchronous call.

Arguments mapping described in
[GetCapacityReservationUsageRequestRequestTypeDef](./type_defs.md#getcapacityreservationusagerequestrequesttypedef).

Keyword-only arguments:

- `CapacityReservationId`: `str` *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`
- `DryRun`: `bool`

Returns a `Coroutine` for
[GetCapacityReservationUsageResultTypeDef](./type_defs.md#getcapacityreservationusageresulttypedef).

<a id="get_coip_pool_usage"></a>

### get_coip_pool_usage

Describes the allocations from the specified customer-owned address pool.

Type annotations for `aiobotocore.create_client("ec2").get_coip_pool_usage`
method.

Boto3 documentation:
[EC2.Client.get_coip_pool_usage](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.get_coip_pool_usage)

Asynchronous method. Use `await get_coip_pool_usage(...)` for a synchronous
call.

Arguments mapping described in
[GetCoipPoolUsageRequestRequestTypeDef](./type_defs.md#getcoippoolusagerequestrequesttypedef).

Keyword-only arguments:

- `PoolId`: `str` *(required)*
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[GetCoipPoolUsageResultTypeDef](./type_defs.md#getcoippoolusageresulttypedef).

<a id="get_console_output"></a>

### get_console_output

Gets the console output for the specified instance.

Type annotations for `aiobotocore.create_client("ec2").get_console_output`
method.

Boto3 documentation:
[EC2.Client.get_console_output](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.get_console_output)

Asynchronous method. Use `await get_console_output(...)` for a synchronous
call.

Arguments mapping described in
[GetConsoleOutputRequestRequestTypeDef](./type_defs.md#getconsoleoutputrequestrequesttypedef).

Keyword-only arguments:

- `InstanceId`: `str` *(required)*
- `DryRun`: `bool`
- `Latest`: `bool`

Returns a `Coroutine` for
[GetConsoleOutputResultTypeDef](./type_defs.md#getconsoleoutputresulttypedef).

<a id="get_console_screenshot"></a>

### get_console_screenshot

Retrieve a JPG-format screenshot of a running instance to help with
troubleshooting.

Type annotations for `aiobotocore.create_client("ec2").get_console_screenshot`
method.

Boto3 documentation:
[EC2.Client.get_console_screenshot](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.get_console_screenshot)

Asynchronous method. Use `await get_console_screenshot(...)` for a synchronous
call.

Arguments mapping described in
[GetConsoleScreenshotRequestRequestTypeDef](./type_defs.md#getconsolescreenshotrequestrequesttypedef).

Keyword-only arguments:

- `InstanceId`: `str` *(required)*
- `DryRun`: `bool`
- `WakeUp`: `bool`

Returns a `Coroutine` for
[GetConsoleScreenshotResultTypeDef](./type_defs.md#getconsolescreenshotresulttypedef).

<a id="get_default_credit_specification"></a>

### get_default_credit_specification

Describes the default credit option for CPU usage of a burstable performance
instance family.

Type annotations for
`aiobotocore.create_client("ec2").get_default_credit_specification` method.

Boto3 documentation:
[EC2.Client.get_default_credit_specification](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.get_default_credit_specification)

Asynchronous method. Use `await get_default_credit_specification(...)` for a
synchronous call.

Arguments mapping described in
[GetDefaultCreditSpecificationRequestRequestTypeDef](./type_defs.md#getdefaultcreditspecificationrequestrequesttypedef).

Keyword-only arguments:

- `InstanceFamily`:
  [UnlimitedSupportedInstanceFamilyType](./literals.md#unlimitedsupportedinstancefamilytype)
  *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[GetDefaultCreditSpecificationResultTypeDef](./type_defs.md#getdefaultcreditspecificationresulttypedef).

<a id="get_ebs_default_kms_key_id"></a>

### get_ebs_default_kms_key_id

Describes the default KMS key for EBS encryption by default for your account in
this Region.

Type annotations for
`aiobotocore.create_client("ec2").get_ebs_default_kms_key_id` method.

Boto3 documentation:
[EC2.Client.get_ebs_default_kms_key_id](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.get_ebs_default_kms_key_id)

Asynchronous method. Use `await get_ebs_default_kms_key_id(...)` for a
synchronous call.

Arguments mapping described in
[GetEbsDefaultKmsKeyIdRequestRequestTypeDef](./type_defs.md#getebsdefaultkmskeyidrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`

Returns a `Coroutine` for
[GetEbsDefaultKmsKeyIdResultTypeDef](./type_defs.md#getebsdefaultkmskeyidresulttypedef).

<a id="get_ebs_encryption_by_default"></a>

### get_ebs_encryption_by_default

Describes whether EBS encryption by default is enabled for your account in the
current Region.

Type annotations for
`aiobotocore.create_client("ec2").get_ebs_encryption_by_default` method.

Boto3 documentation:
[EC2.Client.get_ebs_encryption_by_default](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.get_ebs_encryption_by_default)

Asynchronous method. Use `await get_ebs_encryption_by_default(...)` for a
synchronous call.

Arguments mapping described in
[GetEbsEncryptionByDefaultRequestRequestTypeDef](./type_defs.md#getebsencryptionbydefaultrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`

Returns a `Coroutine` for
[GetEbsEncryptionByDefaultResultTypeDef](./type_defs.md#getebsencryptionbydefaultresulttypedef).

<a id="get_flow_logs_integration_template"></a>

### get_flow_logs_integration_template

Generates a CloudFormation template that streamlines and automates the
integration of VPC flow logs with Amazon Athena.

Type annotations for
`aiobotocore.create_client("ec2").get_flow_logs_integration_template` method.

Boto3 documentation:
[EC2.Client.get_flow_logs_integration_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.get_flow_logs_integration_template)

Asynchronous method. Use `await get_flow_logs_integration_template(...)` for a
synchronous call.

Arguments mapping described in
[GetFlowLogsIntegrationTemplateRequestRequestTypeDef](./type_defs.md#getflowlogsintegrationtemplaterequestrequesttypedef).

Keyword-only arguments:

- `FlowLogId`: `str` *(required)*
- `ConfigDeliveryS3DestinationArn`: `str` *(required)*
- `IntegrateServices`:
  [IntegrateServicesTypeDef](./type_defs.md#integrateservicestypedef)
  *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[GetFlowLogsIntegrationTemplateResultTypeDef](./type_defs.md#getflowlogsintegrationtemplateresulttypedef).

<a id="get_groups_for_capacity_reservation"></a>

### get_groups_for_capacity_reservation

Lists the resource groups to which a Capacity Reservation has been added.

Type annotations for
`aiobotocore.create_client("ec2").get_groups_for_capacity_reservation` method.

Boto3 documentation:
[EC2.Client.get_groups_for_capacity_reservation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.get_groups_for_capacity_reservation)

Asynchronous method. Use `await get_groups_for_capacity_reservation(...)` for a
synchronous call.

Arguments mapping described in
[GetGroupsForCapacityReservationRequestRequestTypeDef](./type_defs.md#getgroupsforcapacityreservationrequestrequesttypedef).

Keyword-only arguments:

- `CapacityReservationId`: `str` *(required)*
- `NextToken`: `str`
- `MaxResults`: `int`
- `DryRun`: `bool`

Returns a `Coroutine` for
[GetGroupsForCapacityReservationResultTypeDef](./type_defs.md#getgroupsforcapacityreservationresulttypedef).

<a id="get_host_reservation_purchase_preview"></a>

### get_host_reservation_purchase_preview

Preview a reservation purchase with configurations that match those of your
Dedicated Host.

Type annotations for
`aiobotocore.create_client("ec2").get_host_reservation_purchase_preview`
method.

Boto3 documentation:
[EC2.Client.get_host_reservation_purchase_preview](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.get_host_reservation_purchase_preview)

Asynchronous method. Use `await get_host_reservation_purchase_preview(...)` for
a synchronous call.

Arguments mapping described in
[GetHostReservationPurchasePreviewRequestRequestTypeDef](./type_defs.md#gethostreservationpurchasepreviewrequestrequesttypedef).

Keyword-only arguments:

- `HostIdSet`: `Sequence`\[`str`\] *(required)*
- `OfferingId`: `str` *(required)*

Returns a `Coroutine` for
[GetHostReservationPurchasePreviewResultTypeDef](./type_defs.md#gethostreservationpurchasepreviewresulttypedef).

<a id="get_instance_types_from_instance_requirements"></a>

### get_instance_types_from_instance_requirements

Returns a list of instance types with the specified instance attributes.

Type annotations for
`aiobotocore.create_client("ec2").get_instance_types_from_instance_requirements`
method.

Boto3 documentation:
[EC2.Client.get_instance_types_from_instance_requirements](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.get_instance_types_from_instance_requirements)

Asynchronous method. Use
`await get_instance_types_from_instance_requirements(...)` for a synchronous
call.

Arguments mapping described in
[GetInstanceTypesFromInstanceRequirementsRequestRequestTypeDef](./type_defs.md#getinstancetypesfrominstancerequirementsrequestrequesttypedef).

Keyword-only arguments:

- `ArchitectureTypes`:
  `Sequence`\[[ArchitectureTypeType](./literals.md#architecturetypetype)\]
  *(required)*
- `VirtualizationTypes`:
  `Sequence`\[[VirtualizationTypeType](./literals.md#virtualizationtypetype)\]
  *(required)*
- `InstanceRequirements`:
  [InstanceRequirementsRequestTypeDef](./type_defs.md#instancerequirementsrequesttypedef)
  *(required)*
- `DryRun`: `bool`
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetInstanceTypesFromInstanceRequirementsResultTypeDef](./type_defs.md#getinstancetypesfrominstancerequirementsresulttypedef).

<a id="get_ipam_address_history"></a>

### get_ipam_address_history

Retrieve historical information about a CIDR within an IPAM scope.

Type annotations for
`aiobotocore.create_client("ec2").get_ipam_address_history` method.

Boto3 documentation:
[EC2.Client.get_ipam_address_history](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.get_ipam_address_history)

Asynchronous method. Use `await get_ipam_address_history(...)` for a
synchronous call.

Arguments mapping described in
[GetIpamAddressHistoryRequestRequestTypeDef](./type_defs.md#getipamaddresshistoryrequestrequesttypedef).

Keyword-only arguments:

- `Cidr`: `str` *(required)*
- `IpamScopeId`: `str` *(required)*
- `DryRun`: `bool`
- `VpcId`: `str`
- `StartTime`: `Union`\[`datetime`, `str`\]
- `EndTime`: `Union`\[`datetime`, `str`\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetIpamAddressHistoryResultTypeDef](./type_defs.md#getipamaddresshistoryresulttypedef).

<a id="get_ipam_pool_allocations"></a>

### get_ipam_pool_allocations

Get a list of all the CIDR allocations in an IPAM pool.

Type annotations for
`aiobotocore.create_client("ec2").get_ipam_pool_allocations` method.

Boto3 documentation:
[EC2.Client.get_ipam_pool_allocations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.get_ipam_pool_allocations)

Asynchronous method. Use `await get_ipam_pool_allocations(...)` for a
synchronous call.

Arguments mapping described in
[GetIpamPoolAllocationsRequestRequestTypeDef](./type_defs.md#getipampoolallocationsrequestrequesttypedef).

Keyword-only arguments:

- `IpamPoolId`: `str` *(required)*
- `DryRun`: `bool`
- `IpamPoolAllocationId`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetIpamPoolAllocationsResultTypeDef](./type_defs.md#getipampoolallocationsresulttypedef).

<a id="get_ipam_pool_cidrs"></a>

### get_ipam_pool_cidrs

Get the CIDRs provisioned to an IPAM pool.

Type annotations for `aiobotocore.create_client("ec2").get_ipam_pool_cidrs`
method.

Boto3 documentation:
[EC2.Client.get_ipam_pool_cidrs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.get_ipam_pool_cidrs)

Asynchronous method. Use `await get_ipam_pool_cidrs(...)` for a synchronous
call.

Arguments mapping described in
[GetIpamPoolCidrsRequestRequestTypeDef](./type_defs.md#getipampoolcidrsrequestrequesttypedef).

Keyword-only arguments:

- `IpamPoolId`: `str` *(required)*
- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetIpamPoolCidrsResultTypeDef](./type_defs.md#getipampoolcidrsresulttypedef).

<a id="get_ipam_resource_cidrs"></a>

### get_ipam_resource_cidrs

Get information about the resources in a scope.

Type annotations for `aiobotocore.create_client("ec2").get_ipam_resource_cidrs`
method.

Boto3 documentation:
[EC2.Client.get_ipam_resource_cidrs](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.get_ipam_resource_cidrs)

Asynchronous method. Use `await get_ipam_resource_cidrs(...)` for a synchronous
call.

Arguments mapping described in
[GetIpamResourceCidrsRequestRequestTypeDef](./type_defs.md#getipamresourcecidrsrequestrequesttypedef).

Keyword-only arguments:

- `IpamScopeId`: `str` *(required)*
- `DryRun`: `bool`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `IpamPoolId`: `str`
- `ResourceId`: `str`
- `ResourceType`: [IpamResourceTypeType](./literals.md#ipamresourcetypetype)
- `ResourceTag`:
  [RequestIpamResourceTagTypeDef](./type_defs.md#requestipamresourcetagtypedef)
- `ResourceOwner`: `str`

Returns a `Coroutine` for
[GetIpamResourceCidrsResultTypeDef](./type_defs.md#getipamresourcecidrsresulttypedef).

<a id="get_launch_template_data"></a>

### get_launch_template_data

Retrieves the configuration data of the specified instance.

Type annotations for
`aiobotocore.create_client("ec2").get_launch_template_data` method.

Boto3 documentation:
[EC2.Client.get_launch_template_data](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.get_launch_template_data)

Asynchronous method. Use `await get_launch_template_data(...)` for a
synchronous call.

Arguments mapping described in
[GetLaunchTemplateDataRequestRequestTypeDef](./type_defs.md#getlaunchtemplatedatarequestrequesttypedef).

Keyword-only arguments:

- `InstanceId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[GetLaunchTemplateDataResultTypeDef](./type_defs.md#getlaunchtemplatedataresulttypedef).

<a id="get_managed_prefix_list_associations"></a>

### get_managed_prefix_list_associations

Gets information about the resources that are associated with the specified
managed prefix list.

Type annotations for
`aiobotocore.create_client("ec2").get_managed_prefix_list_associations` method.

Boto3 documentation:
[EC2.Client.get_managed_prefix_list_associations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.get_managed_prefix_list_associations)

Asynchronous method. Use `await get_managed_prefix_list_associations(...)` for
a synchronous call.

Arguments mapping described in
[GetManagedPrefixListAssociationsRequestRequestTypeDef](./type_defs.md#getmanagedprefixlistassociationsrequestrequesttypedef).

Keyword-only arguments:

- `PrefixListId`: `str` *(required)*
- `DryRun`: `bool`
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetManagedPrefixListAssociationsResultTypeDef](./type_defs.md#getmanagedprefixlistassociationsresulttypedef).

<a id="get_managed_prefix_list_entries"></a>

### get_managed_prefix_list_entries

Gets information about the entries for a specified managed prefix list.

Type annotations for
`aiobotocore.create_client("ec2").get_managed_prefix_list_entries` method.

Boto3 documentation:
[EC2.Client.get_managed_prefix_list_entries](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.get_managed_prefix_list_entries)

Asynchronous method. Use `await get_managed_prefix_list_entries(...)` for a
synchronous call.

Arguments mapping described in
[GetManagedPrefixListEntriesRequestRequestTypeDef](./type_defs.md#getmanagedprefixlistentriesrequestrequesttypedef).

Keyword-only arguments:

- `PrefixListId`: `str` *(required)*
- `DryRun`: `bool`
- `TargetVersion`: `int`
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetManagedPrefixListEntriesResultTypeDef](./type_defs.md#getmanagedprefixlistentriesresulttypedef).

<a id="get_network_insights_access_scope_analysis_findings"></a>

### get_network_insights_access_scope_analysis_findings

Gets the findings for the specified Network Access Scope analysis.

Type annotations for
`aiobotocore.create_client("ec2").get_network_insights_access_scope_analysis_findings`
method.

Boto3 documentation:
[EC2.Client.get_network_insights_access_scope_analysis_findings](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.get_network_insights_access_scope_analysis_findings)

Asynchronous method. Use
`await get_network_insights_access_scope_analysis_findings(...)` for a
synchronous call.

Arguments mapping described in
[GetNetworkInsightsAccessScopeAnalysisFindingsRequestRequestTypeDef](./type_defs.md#getnetworkinsightsaccessscopeanalysisfindingsrequestrequesttypedef).

Keyword-only arguments:

- `NetworkInsightsAccessScopeAnalysisId`: `str` *(required)*
- `MaxResults`: `int`
- `NextToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[GetNetworkInsightsAccessScopeAnalysisFindingsResultTypeDef](./type_defs.md#getnetworkinsightsaccessscopeanalysisfindingsresulttypedef).

<a id="get_network_insights_access_scope_content"></a>

### get_network_insights_access_scope_content

Gets the content for the specified Network Access Scope.

Type annotations for
`aiobotocore.create_client("ec2").get_network_insights_access_scope_content`
method.

Boto3 documentation:
[EC2.Client.get_network_insights_access_scope_content](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.get_network_insights_access_scope_content)

Asynchronous method. Use `await get_network_insights_access_scope_content(...)`
for a synchronous call.

Arguments mapping described in
[GetNetworkInsightsAccessScopeContentRequestRequestTypeDef](./type_defs.md#getnetworkinsightsaccessscopecontentrequestrequesttypedef).

Keyword-only arguments:

- `NetworkInsightsAccessScopeId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[GetNetworkInsightsAccessScopeContentResultTypeDef](./type_defs.md#getnetworkinsightsaccessscopecontentresulttypedef).

<a id="get_password_data"></a>

### get_password_data

Retrieves the encrypted administrator password for a running Windows instance.

Type annotations for `aiobotocore.create_client("ec2").get_password_data`
method.

Boto3 documentation:
[EC2.Client.get_password_data](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.get_password_data)

Asynchronous method. Use `await get_password_data(...)` for a synchronous call.

Arguments mapping described in
[GetPasswordDataRequestRequestTypeDef](./type_defs.md#getpassworddatarequestrequesttypedef).

Keyword-only arguments:

- `InstanceId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[GetPasswordDataResultTypeDef](./type_defs.md#getpassworddataresulttypedef).

<a id="get_reserved_instances_exchange_quote"></a>

### get_reserved_instances_exchange_quote

Returns a quote and exchange information for exchanging one or more specified
Convertible Reserved Instances for a new Convertible Reserved Instance.

Type annotations for
`aiobotocore.create_client("ec2").get_reserved_instances_exchange_quote`
method.

Boto3 documentation:
[EC2.Client.get_reserved_instances_exchange_quote](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.get_reserved_instances_exchange_quote)

Asynchronous method. Use `await get_reserved_instances_exchange_quote(...)` for
a synchronous call.

Arguments mapping described in
[GetReservedInstancesExchangeQuoteRequestRequestTypeDef](./type_defs.md#getreservedinstancesexchangequoterequestrequesttypedef).

Keyword-only arguments:

- `ReservedInstanceIds`: `Sequence`\[`str`\] *(required)*
- `DryRun`: `bool`
- `TargetConfigurations`:
  `Sequence`\[[TargetConfigurationRequestTypeDef](./type_defs.md#targetconfigurationrequesttypedef)\]

Returns a `Coroutine` for
[GetReservedInstancesExchangeQuoteResultTypeDef](./type_defs.md#getreservedinstancesexchangequoteresulttypedef).

<a id="get_serial_console_access_status"></a>

### get_serial_console_access_status

Retrieves the access status of your account to the EC2 serial console of all
instances.

Type annotations for
`aiobotocore.create_client("ec2").get_serial_console_access_status` method.

Boto3 documentation:
[EC2.Client.get_serial_console_access_status](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.get_serial_console_access_status)

Asynchronous method. Use `await get_serial_console_access_status(...)` for a
synchronous call.

Arguments mapping described in
[GetSerialConsoleAccessStatusRequestRequestTypeDef](./type_defs.md#getserialconsoleaccessstatusrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`

Returns a `Coroutine` for
[GetSerialConsoleAccessStatusResultTypeDef](./type_defs.md#getserialconsoleaccessstatusresulttypedef).

<a id="get_spot_placement_scores"></a>

### get_spot_placement_scores

Calculates the Spot placement score for a Region or Availability Zone based on
the specified target capacity and compute requirements.

Type annotations for
`aiobotocore.create_client("ec2").get_spot_placement_scores` method.

Boto3 documentation:
[EC2.Client.get_spot_placement_scores](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.get_spot_placement_scores)

Asynchronous method. Use `await get_spot_placement_scores(...)` for a
synchronous call.

Arguments mapping described in
[GetSpotPlacementScoresRequestRequestTypeDef](./type_defs.md#getspotplacementscoresrequestrequesttypedef).

Keyword-only arguments:

- `TargetCapacity`: `int` *(required)*
- `InstanceTypes`: `Sequence`\[`str`\]
- `TargetCapacityUnitType`:
  [TargetCapacityUnitTypeType](./literals.md#targetcapacityunittypetype)
- `SingleAvailabilityZone`: `bool`
- `RegionNames`: `Sequence`\[`str`\]
- `InstanceRequirementsWithMetadata`:
  [InstanceRequirementsWithMetadataRequestTypeDef](./type_defs.md#instancerequirementswithmetadatarequesttypedef)
- `DryRun`: `bool`
- `MaxResults`: `int`
- `NextToken`: `str`

Returns a `Coroutine` for
[GetSpotPlacementScoresResultTypeDef](./type_defs.md#getspotplacementscoresresulttypedef).

<a id="get_subnet_cidr_reservations"></a>

### get_subnet_cidr_reservations

Gets information about the subnet CIDR reservations.

Type annotations for
`aiobotocore.create_client("ec2").get_subnet_cidr_reservations` method.

Boto3 documentation:
[EC2.Client.get_subnet_cidr_reservations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.get_subnet_cidr_reservations)

Asynchronous method. Use `await get_subnet_cidr_reservations(...)` for a
synchronous call.

Arguments mapping described in
[GetSubnetCidrReservationsRequestRequestTypeDef](./type_defs.md#getsubnetcidrreservationsrequestrequesttypedef).

Keyword-only arguments:

- `SubnetId`: `str` *(required)*
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `DryRun`: `bool`
- `NextToken`: `str`
- `MaxResults`: `int`

Returns a `Coroutine` for
[GetSubnetCidrReservationsResultTypeDef](./type_defs.md#getsubnetcidrreservationsresulttypedef).

<a id="get_transit_gateway_attachment_propagations"></a>

### get_transit_gateway_attachment_propagations

Lists the route tables to which the specified resource attachment propagates
routes.

Type annotations for
`aiobotocore.create_client("ec2").get_transit_gateway_attachment_propagations`
method.

Boto3 documentation:
[EC2.Client.get_transit_gateway_attachment_propagations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.get_transit_gateway_attachment_propagations)

Asynchronous method. Use
`await get_transit_gateway_attachment_propagations(...)` for a synchronous
call.

Arguments mapping described in
[GetTransitGatewayAttachmentPropagationsRequestRequestTypeDef](./type_defs.md#gettransitgatewayattachmentpropagationsrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayAttachmentId`: `str` *(required)*
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[GetTransitGatewayAttachmentPropagationsResultTypeDef](./type_defs.md#gettransitgatewayattachmentpropagationsresulttypedef).

<a id="get_transit_gateway_multicast_domain_associations"></a>

### get_transit_gateway_multicast_domain_associations

Gets information about the associations for the transit gateway multicast
domain.

Type annotations for
`aiobotocore.create_client("ec2").get_transit_gateway_multicast_domain_associations`
method.

Boto3 documentation:
[EC2.Client.get_transit_gateway_multicast_domain_associations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.get_transit_gateway_multicast_domain_associations)

Asynchronous method. Use
`await get_transit_gateway_multicast_domain_associations(...)` for a
synchronous call.

Arguments mapping described in
[GetTransitGatewayMulticastDomainAssociationsRequestRequestTypeDef](./type_defs.md#gettransitgatewaymulticastdomainassociationsrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayMulticastDomainId`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[GetTransitGatewayMulticastDomainAssociationsResultTypeDef](./type_defs.md#gettransitgatewaymulticastdomainassociationsresulttypedef).

<a id="get_transit_gateway_prefix_list_references"></a>

### get_transit_gateway_prefix_list_references

Gets information about the prefix list references in a specified transit
gateway route table.

Type annotations for
`aiobotocore.create_client("ec2").get_transit_gateway_prefix_list_references`
method.

Boto3 documentation:
[EC2.Client.get_transit_gateway_prefix_list_references](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.get_transit_gateway_prefix_list_references)

Asynchronous method. Use
`await get_transit_gateway_prefix_list_references(...)` for a synchronous call.

Arguments mapping described in
[GetTransitGatewayPrefixListReferencesRequestRequestTypeDef](./type_defs.md#gettransitgatewayprefixlistreferencesrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayRouteTableId`: `str` *(required)*
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[GetTransitGatewayPrefixListReferencesResultTypeDef](./type_defs.md#gettransitgatewayprefixlistreferencesresulttypedef).

<a id="get_transit_gateway_route_table_associations"></a>

### get_transit_gateway_route_table_associations

Gets information about the associations for the specified transit gateway route
table.

Type annotations for
`aiobotocore.create_client("ec2").get_transit_gateway_route_table_associations`
method.

Boto3 documentation:
[EC2.Client.get_transit_gateway_route_table_associations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.get_transit_gateway_route_table_associations)

Asynchronous method. Use
`await get_transit_gateway_route_table_associations(...)` for a synchronous
call.

Arguments mapping described in
[GetTransitGatewayRouteTableAssociationsRequestRequestTypeDef](./type_defs.md#gettransitgatewayroutetableassociationsrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayRouteTableId`: `str` *(required)*
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[GetTransitGatewayRouteTableAssociationsResultTypeDef](./type_defs.md#gettransitgatewayroutetableassociationsresulttypedef).

<a id="get_transit_gateway_route_table_propagations"></a>

### get_transit_gateway_route_table_propagations

Gets information about the route table propagations for the specified transit
gateway route table.

Type annotations for
`aiobotocore.create_client("ec2").get_transit_gateway_route_table_propagations`
method.

Boto3 documentation:
[EC2.Client.get_transit_gateway_route_table_propagations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.get_transit_gateway_route_table_propagations)

Asynchronous method. Use
`await get_transit_gateway_route_table_propagations(...)` for a synchronous
call.

Arguments mapping described in
[GetTransitGatewayRouteTablePropagationsRequestRequestTypeDef](./type_defs.md#gettransitgatewayroutetablepropagationsrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayRouteTableId`: `str` *(required)*
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[GetTransitGatewayRouteTablePropagationsResultTypeDef](./type_defs.md#gettransitgatewayroutetablepropagationsresulttypedef).

<a id="get_vpn_connection_device_sample_configuration"></a>

### get_vpn_connection_device_sample_configuration

Download an Amazon Web Services-provided sample configuration file to be used
with the customer gateway device specified for your Site-to-Site VPN
connection.

Type annotations for
`aiobotocore.create_client("ec2").get_vpn_connection_device_sample_configuration`
method.

Boto3 documentation:
[EC2.Client.get_vpn_connection_device_sample_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.get_vpn_connection_device_sample_configuration)

Asynchronous method. Use
`await get_vpn_connection_device_sample_configuration(...)` for a synchronous
call.

Arguments mapping described in
[GetVpnConnectionDeviceSampleConfigurationRequestRequestTypeDef](./type_defs.md#getvpnconnectiondevicesampleconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `VpnConnectionId`: `str` *(required)*
- `VpnConnectionDeviceTypeId`: `str` *(required)*
- `InternetKeyExchangeVersion`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[GetVpnConnectionDeviceSampleConfigurationResultTypeDef](./type_defs.md#getvpnconnectiondevicesampleconfigurationresulttypedef).

<a id="get_vpn_connection_device_types"></a>

### get_vpn_connection_device_types

Obtain a list of customer gateway devices for which sample configuration files
can be provided.

Type annotations for
`aiobotocore.create_client("ec2").get_vpn_connection_device_types` method.

Boto3 documentation:
[EC2.Client.get_vpn_connection_device_types](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.get_vpn_connection_device_types)

Asynchronous method. Use `await get_vpn_connection_device_types(...)` for a
synchronous call.

Arguments mapping described in
[GetVpnConnectionDeviceTypesRequestRequestTypeDef](./type_defs.md#getvpnconnectiondevicetypesrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[GetVpnConnectionDeviceTypesResultTypeDef](./type_defs.md#getvpnconnectiondevicetypesresulttypedef).

<a id="import_client_vpn_client_certificate_revocation_list"></a>

### import_client_vpn_client_certificate_revocation_list

Uploads a client certificate revocation list to the specified Client VPN
endpoint.

Type annotations for
`aiobotocore.create_client("ec2").import_client_vpn_client_certificate_revocation_list`
method.

Boto3 documentation:
[EC2.Client.import_client_vpn_client_certificate_revocation_list](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.import_client_vpn_client_certificate_revocation_list)

Asynchronous method. Use
`await import_client_vpn_client_certificate_revocation_list(...)` for a
synchronous call.

Arguments mapping described in
[ImportClientVpnClientCertificateRevocationListRequestRequestTypeDef](./type_defs.md#importclientvpnclientcertificaterevocationlistrequestrequesttypedef).

Keyword-only arguments:

- `ClientVpnEndpointId`: `str` *(required)*
- `CertificateRevocationList`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[ImportClientVpnClientCertificateRevocationListResultTypeDef](./type_defs.md#importclientvpnclientcertificaterevocationlistresulttypedef).

<a id="import_image"></a>

### import_image

Import single or multi-volume disk images or EBS snapshots into an Amazon
Machine Image (AMI).

Type annotations for `aiobotocore.create_client("ec2").import_image` method.

Boto3 documentation:
[EC2.Client.import_image](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.import_image)

Asynchronous method. Use `await import_image(...)` for a synchronous call.

Arguments mapping described in
[ImportImageRequestRequestTypeDef](./type_defs.md#importimagerequestrequesttypedef).

Keyword-only arguments:

- `Architecture`: `str`
- `ClientData`: [ClientDataTypeDef](./type_defs.md#clientdatatypedef)
- `ClientToken`: `str`
- `Description`: `str`
- `DiskContainers`:
  `Sequence`\[[ImageDiskContainerTypeDef](./type_defs.md#imagediskcontainertypedef)\]
- `DryRun`: `bool`
- `Encrypted`: `bool`
- `Hypervisor`: `str`
- `KmsKeyId`: `str`
- `LicenseType`: `str`
- `Platform`: `str`
- `RoleName`: `str`
- `LicenseSpecifications`:
  `Sequence`\[[ImportImageLicenseConfigurationRequestTypeDef](./type_defs.md#importimagelicenseconfigurationrequesttypedef)\]
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `UsageOperation`: `str`
- `BootMode`: [BootModeValuesType](./literals.md#bootmodevaluestype)

Returns a `Coroutine` for
[ImportImageResultTypeDef](./type_defs.md#importimageresulttypedef).

<a id="import_instance"></a>

### import_instance

Creates an import instance task using metadata from the specified disk image.

Type annotations for `aiobotocore.create_client("ec2").import_instance` method.

Boto3 documentation:
[EC2.Client.import_instance](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.import_instance)

Asynchronous method. Use `await import_instance(...)` for a synchronous call.

Arguments mapping described in
[ImportInstanceRequestRequestTypeDef](./type_defs.md#importinstancerequestrequesttypedef).

Keyword-only arguments:

- `Platform`: `Literal['Windows']` (see
  [PlatformValuesType](./literals.md#platformvaluestype)) *(required)*
- `Description`: `str`
- `DiskImages`:
  `Sequence`\[[DiskImageTypeDef](./type_defs.md#diskimagetypedef)\]
- `DryRun`: `bool`
- `LaunchSpecification`:
  [ImportInstanceLaunchSpecificationTypeDef](./type_defs.md#importinstancelaunchspecificationtypedef)

Returns a `Coroutine` for
[ImportInstanceResultTypeDef](./type_defs.md#importinstanceresulttypedef).

<a id="import_key_pair"></a>

### import_key_pair

Imports the public key from an RSA or ED25519 key pair that you created with a
third-party tool.

Type annotations for `aiobotocore.create_client("ec2").import_key_pair` method.

Boto3 documentation:
[EC2.Client.import_key_pair](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.import_key_pair)

Asynchronous method. Use `await import_key_pair(...)` for a synchronous call.

Arguments mapping described in
[ImportKeyPairRequestRequestTypeDef](./type_defs.md#importkeypairrequestrequesttypedef).

Keyword-only arguments:

- `KeyName`: `str` *(required)*
- `PublicKeyMaterial`: `Union`\[`bytes`, `IO`\[`bytes`\], `StreamingBody`\]
  *(required)*
- `DryRun`: `bool`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for
[ImportKeyPairResultTypeDef](./type_defs.md#importkeypairresulttypedef).

<a id="import_snapshot"></a>

### import_snapshot

Imports a disk into an EBS snapshot.

Type annotations for `aiobotocore.create_client("ec2").import_snapshot` method.

Boto3 documentation:
[EC2.Client.import_snapshot](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.import_snapshot)

Asynchronous method. Use `await import_snapshot(...)` for a synchronous call.

Arguments mapping described in
[ImportSnapshotRequestRequestTypeDef](./type_defs.md#importsnapshotrequestrequesttypedef).

Keyword-only arguments:

- `ClientData`: [ClientDataTypeDef](./type_defs.md#clientdatatypedef)
- `ClientToken`: `str`
- `Description`: `str`
- `DiskContainer`:
  [SnapshotDiskContainerTypeDef](./type_defs.md#snapshotdiskcontainertypedef)
- `DryRun`: `bool`
- `Encrypted`: `bool`
- `KmsKeyId`: `str`
- `RoleName`: `str`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for
[ImportSnapshotResultTypeDef](./type_defs.md#importsnapshotresulttypedef).

<a id="import_volume"></a>

### import_volume

Creates an import volume task using metadata from the specified disk image.

Type annotations for `aiobotocore.create_client("ec2").import_volume` method.

Boto3 documentation:
[EC2.Client.import_volume](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.import_volume)

Asynchronous method. Use `await import_volume(...)` for a synchronous call.

Arguments mapping described in
[ImportVolumeRequestRequestTypeDef](./type_defs.md#importvolumerequestrequesttypedef).

Keyword-only arguments:

- `AvailabilityZone`: `str` *(required)*
- `Image`: [DiskImageDetailTypeDef](./type_defs.md#diskimagedetailtypedef)
  *(required)*
- `Volume`: [VolumeDetailTypeDef](./type_defs.md#volumedetailtypedef)
  *(required)*
- `Description`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[ImportVolumeResultTypeDef](./type_defs.md#importvolumeresulttypedef).

<a id="list_snapshots_in_recycle_bin"></a>

### list_snapshots_in_recycle_bin

Lists one or more snapshots that are currently in the Recycle Bin.

Type annotations for
`aiobotocore.create_client("ec2").list_snapshots_in_recycle_bin` method.

Boto3 documentation:
[EC2.Client.list_snapshots_in_recycle_bin](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.list_snapshots_in_recycle_bin)

Asynchronous method. Use `await list_snapshots_in_recycle_bin(...)` for a
synchronous call.

Arguments mapping described in
[ListSnapshotsInRecycleBinRequestRequestTypeDef](./type_defs.md#listsnapshotsinrecyclebinrequestrequesttypedef).

Keyword-only arguments:

- `MaxResults`: `int`
- `NextToken`: `str`
- `SnapshotIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[ListSnapshotsInRecycleBinResultTypeDef](./type_defs.md#listsnapshotsinrecyclebinresulttypedef).

<a id="modify_address_attribute"></a>

### modify_address_attribute

Modifies an attribute of the specified Elastic IP address.

Type annotations for
`aiobotocore.create_client("ec2").modify_address_attribute` method.

Boto3 documentation:
[EC2.Client.modify_address_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_address_attribute)

Asynchronous method. Use `await modify_address_attribute(...)` for a
synchronous call.

Arguments mapping described in
[ModifyAddressAttributeRequestRequestTypeDef](./type_defs.md#modifyaddressattributerequestrequesttypedef).

Keyword-only arguments:

- `AllocationId`: `str` *(required)*
- `DomainName`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[ModifyAddressAttributeResultTypeDef](./type_defs.md#modifyaddressattributeresulttypedef).

<a id="modify_availability_zone_group"></a>

### modify_availability_zone_group

Changes the opt-in status of the Local Zone and Wavelength Zone group for your
account.

Type annotations for
`aiobotocore.create_client("ec2").modify_availability_zone_group` method.

Boto3 documentation:
[EC2.Client.modify_availability_zone_group](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_availability_zone_group)

Asynchronous method. Use `await modify_availability_zone_group(...)` for a
synchronous call.

Arguments mapping described in
[ModifyAvailabilityZoneGroupRequestRequestTypeDef](./type_defs.md#modifyavailabilityzonegrouprequestrequesttypedef).

Keyword-only arguments:

- `GroupName`: `str` *(required)*
- `OptInStatus`:
  [ModifyAvailabilityZoneOptInStatusType](./literals.md#modifyavailabilityzoneoptinstatustype)
  *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[ModifyAvailabilityZoneGroupResultTypeDef](./type_defs.md#modifyavailabilityzonegroupresulttypedef).

<a id="modify_capacity_reservation"></a>

### modify_capacity_reservation

Modifies a Capacity Reservation's capacity and the conditions under which it is
to be released.

Type annotations for
`aiobotocore.create_client("ec2").modify_capacity_reservation` method.

Boto3 documentation:
[EC2.Client.modify_capacity_reservation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_capacity_reservation)

Asynchronous method. Use `await modify_capacity_reservation(...)` for a
synchronous call.

Arguments mapping described in
[ModifyCapacityReservationRequestRequestTypeDef](./type_defs.md#modifycapacityreservationrequestrequesttypedef).

Keyword-only arguments:

- `CapacityReservationId`: `str` *(required)*
- `InstanceCount`: `int`
- `EndDate`: `Union`\[`datetime`, `str`\]
- `EndDateType`: [EndDateTypeType](./literals.md#enddatetypetype)
- `Accept`: `bool`
- `DryRun`: `bool`
- `AdditionalInfo`: `str`

Returns a `Coroutine` for
[ModifyCapacityReservationResultTypeDef](./type_defs.md#modifycapacityreservationresulttypedef).

<a id="modify_capacity_reservation_fleet"></a>

### modify_capacity_reservation_fleet

Modifies a Capacity Reservation Fleet.

Type annotations for
`aiobotocore.create_client("ec2").modify_capacity_reservation_fleet` method.

Boto3 documentation:
[EC2.Client.modify_capacity_reservation_fleet](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_capacity_reservation_fleet)

Asynchronous method. Use `await modify_capacity_reservation_fleet(...)` for a
synchronous call.

Arguments mapping described in
[ModifyCapacityReservationFleetRequestRequestTypeDef](./type_defs.md#modifycapacityreservationfleetrequestrequesttypedef).

Keyword-only arguments:

- `CapacityReservationFleetId`: `str` *(required)*
- `TotalTargetCapacity`: `int`
- `EndDate`: `Union`\[`datetime`, `str`\]
- `DryRun`: `bool`
- `RemoveEndDate`: `bool`

Returns a `Coroutine` for
[ModifyCapacityReservationFleetResultTypeDef](./type_defs.md#modifycapacityreservationfleetresulttypedef).

<a id="modify_client_vpn_endpoint"></a>

### modify_client_vpn_endpoint

Modifies the specified Client VPN endpoint.

Type annotations for
`aiobotocore.create_client("ec2").modify_client_vpn_endpoint` method.

Boto3 documentation:
[EC2.Client.modify_client_vpn_endpoint](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_client_vpn_endpoint)

Asynchronous method. Use `await modify_client_vpn_endpoint(...)` for a
synchronous call.

Arguments mapping described in
[ModifyClientVpnEndpointRequestRequestTypeDef](./type_defs.md#modifyclientvpnendpointrequestrequesttypedef).

Keyword-only arguments:

- `ClientVpnEndpointId`: `str` *(required)*
- `ServerCertificateArn`: `str`
- `ConnectionLogOptions`:
  [ConnectionLogOptionsTypeDef](./type_defs.md#connectionlogoptionstypedef)
- `DnsServers`:
  [DnsServersOptionsModifyStructureTypeDef](./type_defs.md#dnsserversoptionsmodifystructuretypedef)
- `VpnPort`: `int`
- `Description`: `str`
- `SplitTunnel`: `bool`
- `DryRun`: `bool`
- `SecurityGroupIds`: `Sequence`\[`str`\]
- `VpcId`: `str`
- `SelfServicePortal`:
  [SelfServicePortalType](./literals.md#selfserviceportaltype)
- `ClientConnectOptions`:
  [ClientConnectOptionsTypeDef](./type_defs.md#clientconnectoptionstypedef)

Returns a `Coroutine` for
[ModifyClientVpnEndpointResultTypeDef](./type_defs.md#modifyclientvpnendpointresulttypedef).

<a id="modify_default_credit_specification"></a>

### modify_default_credit_specification

Modifies the default credit option for CPU usage of burstable performance
instances.

Type annotations for
`aiobotocore.create_client("ec2").modify_default_credit_specification` method.

Boto3 documentation:
[EC2.Client.modify_default_credit_specification](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_default_credit_specification)

Asynchronous method. Use `await modify_default_credit_specification(...)` for a
synchronous call.

Arguments mapping described in
[ModifyDefaultCreditSpecificationRequestRequestTypeDef](./type_defs.md#modifydefaultcreditspecificationrequestrequesttypedef).

Keyword-only arguments:

- `InstanceFamily`:
  [UnlimitedSupportedInstanceFamilyType](./literals.md#unlimitedsupportedinstancefamilytype)
  *(required)*
- `CpuCredits`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[ModifyDefaultCreditSpecificationResultTypeDef](./type_defs.md#modifydefaultcreditspecificationresulttypedef).

<a id="modify_ebs_default_kms_key_id"></a>

### modify_ebs_default_kms_key_id

Changes the default KMS key for EBS encryption by default for your account in
this Region.

Type annotations for
`aiobotocore.create_client("ec2").modify_ebs_default_kms_key_id` method.

Boto3 documentation:
[EC2.Client.modify_ebs_default_kms_key_id](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_ebs_default_kms_key_id)

Asynchronous method. Use `await modify_ebs_default_kms_key_id(...)` for a
synchronous call.

Arguments mapping described in
[ModifyEbsDefaultKmsKeyIdRequestRequestTypeDef](./type_defs.md#modifyebsdefaultkmskeyidrequestrequesttypedef).

Keyword-only arguments:

- `KmsKeyId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[ModifyEbsDefaultKmsKeyIdResultTypeDef](./type_defs.md#modifyebsdefaultkmskeyidresulttypedef).

<a id="modify_fleet"></a>

### modify_fleet

Modifies the specified EC2 Fleet.

Type annotations for `aiobotocore.create_client("ec2").modify_fleet` method.

Boto3 documentation:
[EC2.Client.modify_fleet](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_fleet)

Asynchronous method. Use `await modify_fleet(...)` for a synchronous call.

Arguments mapping described in
[ModifyFleetRequestRequestTypeDef](./type_defs.md#modifyfleetrequestrequesttypedef).

Keyword-only arguments:

- `FleetId`: `str` *(required)*
- `DryRun`: `bool`
- `ExcessCapacityTerminationPolicy`:
  [FleetExcessCapacityTerminationPolicyType](./literals.md#fleetexcesscapacityterminationpolicytype)
- `LaunchTemplateConfigs`:
  `Sequence`\[[FleetLaunchTemplateConfigRequestTypeDef](./type_defs.md#fleetlaunchtemplateconfigrequesttypedef)\]
- `TargetCapacitySpecification`:
  [TargetCapacitySpecificationRequestTypeDef](./type_defs.md#targetcapacityspecificationrequesttypedef)
- `Context`: `str`

Returns a `Coroutine` for
[ModifyFleetResultTypeDef](./type_defs.md#modifyfleetresulttypedef).

<a id="modify_fpga_image_attribute"></a>

### modify_fpga_image_attribute

Modifies the specified attribute of the specified Amazon FPGA Image (AFI).

Type annotations for
`aiobotocore.create_client("ec2").modify_fpga_image_attribute` method.

Boto3 documentation:
[EC2.Client.modify_fpga_image_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_fpga_image_attribute)

Asynchronous method. Use `await modify_fpga_image_attribute(...)` for a
synchronous call.

Arguments mapping described in
[ModifyFpgaImageAttributeRequestRequestTypeDef](./type_defs.md#modifyfpgaimageattributerequestrequesttypedef).

Keyword-only arguments:

- `FpgaImageId`: `str` *(required)*
- `DryRun`: `bool`
- `Attribute`:
  [FpgaImageAttributeNameType](./literals.md#fpgaimageattributenametype)
- `OperationType`: [OperationTypeType](./literals.md#operationtypetype)
- `UserIds`: `Sequence`\[`str`\]
- `UserGroups`: `Sequence`\[`str`\]
- `ProductCodes`: `Sequence`\[`str`\]
- `LoadPermission`:
  [LoadPermissionModificationsTypeDef](./type_defs.md#loadpermissionmodificationstypedef)
- `Description`: `str`
- `Name`: `str`

Returns a `Coroutine` for
[ModifyFpgaImageAttributeResultTypeDef](./type_defs.md#modifyfpgaimageattributeresulttypedef).

<a id="modify_hosts"></a>

### modify_hosts

Modify the auto-placement setting of a Dedicated Host.

Type annotations for `aiobotocore.create_client("ec2").modify_hosts` method.

Boto3 documentation:
[EC2.Client.modify_hosts](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_hosts)

Asynchronous method. Use `await modify_hosts(...)` for a synchronous call.

Arguments mapping described in
[ModifyHostsRequestRequestTypeDef](./type_defs.md#modifyhostsrequestrequesttypedef).

Keyword-only arguments:

- `HostIds`: `Sequence`\[`str`\] *(required)*
- `AutoPlacement`: [AutoPlacementType](./literals.md#autoplacementtype)
- `HostRecovery`: [HostRecoveryType](./literals.md#hostrecoverytype)
- `InstanceType`: `str`
- `InstanceFamily`: `str`

Returns a `Coroutine` for
[ModifyHostsResultTypeDef](./type_defs.md#modifyhostsresulttypedef).

<a id="modify_id_format"></a>

### modify_id_format

Modifies the ID format for the specified resource on a per-Region basis.

Type annotations for `aiobotocore.create_client("ec2").modify_id_format`
method.

Boto3 documentation:
[EC2.Client.modify_id_format](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_id_format)

Asynchronous method. Use `await modify_id_format(...)` for a synchronous call.

Arguments mapping described in
[ModifyIdFormatRequestRequestTypeDef](./type_defs.md#modifyidformatrequestrequesttypedef).

Keyword-only arguments:

- `Resource`: `str` *(required)*
- `UseLongIds`: `bool` *(required)*

<a id="modify_identity_id_format"></a>

### modify_identity_id_format

Modifies the ID format of a resource for a specified IAM user, IAM role, or the
root user for an account; or all IAM users, IAM roles, and the root user for an
account.

Type annotations for
`aiobotocore.create_client("ec2").modify_identity_id_format` method.

Boto3 documentation:
[EC2.Client.modify_identity_id_format](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_identity_id_format)

Asynchronous method. Use `await modify_identity_id_format(...)` for a
synchronous call.

Arguments mapping described in
[ModifyIdentityIdFormatRequestRequestTypeDef](./type_defs.md#modifyidentityidformatrequestrequesttypedef).

Keyword-only arguments:

- `PrincipalArn`: `str` *(required)*
- `Resource`: `str` *(required)*
- `UseLongIds`: `bool` *(required)*

<a id="modify_image_attribute"></a>

### modify_image_attribute

Modifies the specified attribute of the specified AMI.

Type annotations for `aiobotocore.create_client("ec2").modify_image_attribute`
method.

Boto3 documentation:
[EC2.Client.modify_image_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_image_attribute)

Asynchronous method. Use `await modify_image_attribute(...)` for a synchronous
call.

Arguments mapping described in
[ModifyImageAttributeRequestRequestTypeDef](./type_defs.md#modifyimageattributerequestrequesttypedef).

Keyword-only arguments:

- `ImageId`: `str` *(required)*
- `Attribute`: `str`
- `Description`: [AttributeValueTypeDef](./type_defs.md#attributevaluetypedef)
- `LaunchPermission`:
  [LaunchPermissionModificationsTypeDef](./type_defs.md#launchpermissionmodificationstypedef)
- `OperationType`: [OperationTypeType](./literals.md#operationtypetype)
- `ProductCodes`: `Sequence`\[`str`\]
- `UserGroups`: `Sequence`\[`str`\]
- `UserIds`: `Sequence`\[`str`\]
- `Value`: `str`
- `DryRun`: `bool`
- `OrganizationArns`: `Sequence`\[`str`\]
- `OrganizationalUnitArns`: `Sequence`\[`str`\]

<a id="modify_instance_attribute"></a>

### modify_instance_attribute

Modifies the specified attribute of the specified instance.

Type annotations for
`aiobotocore.create_client("ec2").modify_instance_attribute` method.

Boto3 documentation:
[EC2.Client.modify_instance_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_instance_attribute)

Asynchronous method. Use `await modify_instance_attribute(...)` for a
synchronous call.

Arguments mapping described in
[ModifyInstanceAttributeRequestRequestTypeDef](./type_defs.md#modifyinstanceattributerequestrequesttypedef).

Keyword-only arguments:

- `InstanceId`: `str` *(required)*
- `SourceDestCheck`:
  [AttributeBooleanValueTypeDef](./type_defs.md#attributebooleanvaluetypedef)
- `Attribute`:
  [InstanceAttributeNameType](./literals.md#instanceattributenametype)
- `BlockDeviceMappings`:
  `Sequence`\[[InstanceBlockDeviceMappingSpecificationTypeDef](./type_defs.md#instanceblockdevicemappingspecificationtypedef)\]
- `DisableApiTermination`:
  [AttributeBooleanValueTypeDef](./type_defs.md#attributebooleanvaluetypedef)
- `DryRun`: `bool`
- `EbsOptimized`:
  [AttributeBooleanValueTypeDef](./type_defs.md#attributebooleanvaluetypedef)
- `EnaSupport`:
  [AttributeBooleanValueTypeDef](./type_defs.md#attributebooleanvaluetypedef)
- `Groups`: `Sequence`\[`str`\]
- `InstanceInitiatedShutdownBehavior`:
  [AttributeValueTypeDef](./type_defs.md#attributevaluetypedef)
- `InstanceType`: [AttributeValueTypeDef](./type_defs.md#attributevaluetypedef)
- `Kernel`: [AttributeValueTypeDef](./type_defs.md#attributevaluetypedef)
- `Ramdisk`: [AttributeValueTypeDef](./type_defs.md#attributevaluetypedef)
- `SriovNetSupport`:
  [AttributeValueTypeDef](./type_defs.md#attributevaluetypedef)
- `UserData`:
  [BlobAttributeValueTypeDef](./type_defs.md#blobattributevaluetypedef)
- `Value`: `str`

<a id="modify_instance_capacity_reservation_attributes"></a>

### modify_instance_capacity_reservation_attributes

Modifies the Capacity Reservation settings for a stopped instance.

Type annotations for
`aiobotocore.create_client("ec2").modify_instance_capacity_reservation_attributes`
method.

Boto3 documentation:
[EC2.Client.modify_instance_capacity_reservation_attributes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_instance_capacity_reservation_attributes)

Asynchronous method. Use
`await modify_instance_capacity_reservation_attributes(...)` for a synchronous
call.

Arguments mapping described in
[ModifyInstanceCapacityReservationAttributesRequestRequestTypeDef](./type_defs.md#modifyinstancecapacityreservationattributesrequestrequesttypedef).

Keyword-only arguments:

- `InstanceId`: `str` *(required)*
- `CapacityReservationSpecification`:
  [CapacityReservationSpecificationTypeDef](./type_defs.md#capacityreservationspecificationtypedef)
  *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[ModifyInstanceCapacityReservationAttributesResultTypeDef](./type_defs.md#modifyinstancecapacityreservationattributesresulttypedef).

<a id="modify_instance_credit_specification"></a>

### modify_instance_credit_specification

Modifies the credit option for CPU usage on a running or stopped burstable
performance instance.

Type annotations for
`aiobotocore.create_client("ec2").modify_instance_credit_specification` method.

Boto3 documentation:
[EC2.Client.modify_instance_credit_specification](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_instance_credit_specification)

Asynchronous method. Use `await modify_instance_credit_specification(...)` for
a synchronous call.

Arguments mapping described in
[ModifyInstanceCreditSpecificationRequestRequestTypeDef](./type_defs.md#modifyinstancecreditspecificationrequestrequesttypedef).

Keyword-only arguments:

- `InstanceCreditSpecifications`:
  `Sequence`\[[InstanceCreditSpecificationRequestTypeDef](./type_defs.md#instancecreditspecificationrequesttypedef)\]
  *(required)*
- `DryRun`: `bool`
- `ClientToken`: `str`

Returns a `Coroutine` for
[ModifyInstanceCreditSpecificationResultTypeDef](./type_defs.md#modifyinstancecreditspecificationresulttypedef).

<a id="modify_instance_event_start_time"></a>

### modify_instance_event_start_time

Modifies the start time for a scheduled Amazon EC2 instance event.

Type annotations for
`aiobotocore.create_client("ec2").modify_instance_event_start_time` method.

Boto3 documentation:
[EC2.Client.modify_instance_event_start_time](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_instance_event_start_time)

Asynchronous method. Use `await modify_instance_event_start_time(...)` for a
synchronous call.

Arguments mapping described in
[ModifyInstanceEventStartTimeRequestRequestTypeDef](./type_defs.md#modifyinstanceeventstarttimerequestrequesttypedef).

Keyword-only arguments:

- `InstanceId`: `str` *(required)*
- `InstanceEventId`: `str` *(required)*
- `NotBefore`: `Union`\[`datetime`, `str`\] *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[ModifyInstanceEventStartTimeResultTypeDef](./type_defs.md#modifyinstanceeventstarttimeresulttypedef).

<a id="modify_instance_event_window"></a>

### modify_instance_event_window

Modifies the specified event window.

Type annotations for
`aiobotocore.create_client("ec2").modify_instance_event_window` method.

Boto3 documentation:
[EC2.Client.modify_instance_event_window](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_instance_event_window)

Asynchronous method. Use `await modify_instance_event_window(...)` for a
synchronous call.

Arguments mapping described in
[ModifyInstanceEventWindowRequestRequestTypeDef](./type_defs.md#modifyinstanceeventwindowrequestrequesttypedef).

Keyword-only arguments:

- `InstanceEventWindowId`: `str` *(required)*
- `DryRun`: `bool`
- `Name`: `str`
- `TimeRanges`:
  `Sequence`\[[InstanceEventWindowTimeRangeRequestTypeDef](./type_defs.md#instanceeventwindowtimerangerequesttypedef)\]
- `CronExpression`: `str`

Returns a `Coroutine` for
[ModifyInstanceEventWindowResultTypeDef](./type_defs.md#modifyinstanceeventwindowresulttypedef).

<a id="modify_instance_metadata_options"></a>

### modify_instance_metadata_options

Modify the instance metadata parameters on a running or stopped instance.

Type annotations for
`aiobotocore.create_client("ec2").modify_instance_metadata_options` method.

Boto3 documentation:
[EC2.Client.modify_instance_metadata_options](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_instance_metadata_options)

Asynchronous method. Use `await modify_instance_metadata_options(...)` for a
synchronous call.

Arguments mapping described in
[ModifyInstanceMetadataOptionsRequestRequestTypeDef](./type_defs.md#modifyinstancemetadataoptionsrequestrequesttypedef).

Keyword-only arguments:

- `InstanceId`: `str` *(required)*
- `HttpTokens`: [HttpTokensStateType](./literals.md#httptokensstatetype)
- `HttpPutResponseHopLimit`: `int`
- `HttpEndpoint`:
  [InstanceMetadataEndpointStateType](./literals.md#instancemetadataendpointstatetype)
- `DryRun`: `bool`
- `HttpProtocolIpv6`:
  [InstanceMetadataProtocolStateType](./literals.md#instancemetadataprotocolstatetype)

Returns a `Coroutine` for
[ModifyInstanceMetadataOptionsResultTypeDef](./type_defs.md#modifyinstancemetadataoptionsresulttypedef).

<a id="modify_instance_placement"></a>

### modify_instance_placement

Modifies the placement attributes for a specified instance.

Type annotations for
`aiobotocore.create_client("ec2").modify_instance_placement` method.

Boto3 documentation:
[EC2.Client.modify_instance_placement](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_instance_placement)

Asynchronous method. Use `await modify_instance_placement(...)` for a
synchronous call.

Arguments mapping described in
[ModifyInstancePlacementRequestRequestTypeDef](./type_defs.md#modifyinstanceplacementrequestrequesttypedef).

Keyword-only arguments:

- `InstanceId`: `str` *(required)*
- `Affinity`: [AffinityType](./literals.md#affinitytype)
- `GroupName`: `str`
- `HostId`: `str`
- `Tenancy`: [HostTenancyType](./literals.md#hosttenancytype)
- `PartitionNumber`: `int`
- `HostResourceGroupArn`: `str`

Returns a `Coroutine` for
[ModifyInstancePlacementResultTypeDef](./type_defs.md#modifyinstanceplacementresulttypedef).

<a id="modify_ipam"></a>

### modify_ipam

Modify the configurations of an IPAM.

Type annotations for `aiobotocore.create_client("ec2").modify_ipam` method.

Boto3 documentation:
[EC2.Client.modify_ipam](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_ipam)

Asynchronous method. Use `await modify_ipam(...)` for a synchronous call.

Arguments mapping described in
[ModifyIpamRequestRequestTypeDef](./type_defs.md#modifyipamrequestrequesttypedef).

Keyword-only arguments:

- `IpamId`: `str` *(required)*
- `DryRun`: `bool`
- `Description`: `str`
- `AddOperatingRegions`:
  `Sequence`\[[AddIpamOperatingRegionTypeDef](./type_defs.md#addipamoperatingregiontypedef)\]
- `RemoveOperatingRegions`:
  `Sequence`\[[RemoveIpamOperatingRegionTypeDef](./type_defs.md#removeipamoperatingregiontypedef)\]

Returns a `Coroutine` for
[ModifyIpamResultTypeDef](./type_defs.md#modifyipamresulttypedef).

<a id="modify_ipam_pool"></a>

### modify_ipam_pool

Modify the configurations of an IPAM pool.

Type annotations for `aiobotocore.create_client("ec2").modify_ipam_pool`
method.

Boto3 documentation:
[EC2.Client.modify_ipam_pool](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_ipam_pool)

Asynchronous method. Use `await modify_ipam_pool(...)` for a synchronous call.

Arguments mapping described in
[ModifyIpamPoolRequestRequestTypeDef](./type_defs.md#modifyipampoolrequestrequesttypedef).

Keyword-only arguments:

- `IpamPoolId`: `str` *(required)*
- `DryRun`: `bool`
- `Description`: `str`
- `AutoImport`: `bool`
- `AllocationMinNetmaskLength`: `int`
- `AllocationMaxNetmaskLength`: `int`
- `AllocationDefaultNetmaskLength`: `int`
- `ClearAllocationDefaultNetmaskLength`: `bool`
- `AddAllocationResourceTags`:
  `Sequence`\[[RequestIpamResourceTagTypeDef](./type_defs.md#requestipamresourcetagtypedef)\]
- `RemoveAllocationResourceTags`:
  `Sequence`\[[RequestIpamResourceTagTypeDef](./type_defs.md#requestipamresourcetagtypedef)\]

Returns a `Coroutine` for
[ModifyIpamPoolResultTypeDef](./type_defs.md#modifyipampoolresulttypedef).

<a id="modify_ipam_resource_cidr"></a>

### modify_ipam_resource_cidr

Modify a resource CIDR.

Type annotations for
`aiobotocore.create_client("ec2").modify_ipam_resource_cidr` method.

Boto3 documentation:
[EC2.Client.modify_ipam_resource_cidr](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_ipam_resource_cidr)

Asynchronous method. Use `await modify_ipam_resource_cidr(...)` for a
synchronous call.

Arguments mapping described in
[ModifyIpamResourceCidrRequestRequestTypeDef](./type_defs.md#modifyipamresourcecidrrequestrequesttypedef).

Keyword-only arguments:

- `ResourceId`: `str` *(required)*
- `ResourceCidr`: `str` *(required)*
- `ResourceRegion`: `str` *(required)*
- `CurrentIpamScopeId`: `str` *(required)*
- `Monitored`: `bool` *(required)*
- `DryRun`: `bool`
- `DestinationIpamScopeId`: `str`

Returns a `Coroutine` for
[ModifyIpamResourceCidrResultTypeDef](./type_defs.md#modifyipamresourcecidrresulttypedef).

<a id="modify_ipam_scope"></a>

### modify_ipam_scope

Modify an IPAM scope.

Type annotations for `aiobotocore.create_client("ec2").modify_ipam_scope`
method.

Boto3 documentation:
[EC2.Client.modify_ipam_scope](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_ipam_scope)

Asynchronous method. Use `await modify_ipam_scope(...)` for a synchronous call.

Arguments mapping described in
[ModifyIpamScopeRequestRequestTypeDef](./type_defs.md#modifyipamscoperequestrequesttypedef).

Keyword-only arguments:

- `IpamScopeId`: `str` *(required)*
- `DryRun`: `bool`
- `Description`: `str`

Returns a `Coroutine` for
[ModifyIpamScopeResultTypeDef](./type_defs.md#modifyipamscoperesulttypedef).

<a id="modify_launch_template"></a>

### modify_launch_template

Modifies a launch template.

Type annotations for `aiobotocore.create_client("ec2").modify_launch_template`
method.

Boto3 documentation:
[EC2.Client.modify_launch_template](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_launch_template)

Asynchronous method. Use `await modify_launch_template(...)` for a synchronous
call.

Arguments mapping described in
[ModifyLaunchTemplateRequestRequestTypeDef](./type_defs.md#modifylaunchtemplaterequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `ClientToken`: `str`
- `LaunchTemplateId`: `str`
- `LaunchTemplateName`: `str`
- `DefaultVersion`: `str`

Returns a `Coroutine` for
[ModifyLaunchTemplateResultTypeDef](./type_defs.md#modifylaunchtemplateresulttypedef).

<a id="modify_managed_prefix_list"></a>

### modify_managed_prefix_list

Modifies the specified managed prefix list.

Type annotations for
`aiobotocore.create_client("ec2").modify_managed_prefix_list` method.

Boto3 documentation:
[EC2.Client.modify_managed_prefix_list](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_managed_prefix_list)

Asynchronous method. Use `await modify_managed_prefix_list(...)` for a
synchronous call.

Arguments mapping described in
[ModifyManagedPrefixListRequestRequestTypeDef](./type_defs.md#modifymanagedprefixlistrequestrequesttypedef).

Keyword-only arguments:

- `PrefixListId`: `str` *(required)*
- `DryRun`: `bool`
- `CurrentVersion`: `int`
- `PrefixListName`: `str`
- `AddEntries`:
  `Sequence`\[[AddPrefixListEntryTypeDef](./type_defs.md#addprefixlistentrytypedef)\]
- `RemoveEntries`:
  `Sequence`\[[RemovePrefixListEntryTypeDef](./type_defs.md#removeprefixlistentrytypedef)\]
- `MaxEntries`: `int`

Returns a `Coroutine` for
[ModifyManagedPrefixListResultTypeDef](./type_defs.md#modifymanagedprefixlistresulttypedef).

<a id="modify_network_interface_attribute"></a>

### modify_network_interface_attribute

Modifies the specified network interface attribute.

Type annotations for
`aiobotocore.create_client("ec2").modify_network_interface_attribute` method.

Boto3 documentation:
[EC2.Client.modify_network_interface_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_network_interface_attribute)

Asynchronous method. Use `await modify_network_interface_attribute(...)` for a
synchronous call.

Arguments mapping described in
[ModifyNetworkInterfaceAttributeRequestRequestTypeDef](./type_defs.md#modifynetworkinterfaceattributerequestrequesttypedef).

Keyword-only arguments:

- `NetworkInterfaceId`: `str` *(required)*
- `Attachment`:
  [NetworkInterfaceAttachmentChangesTypeDef](./type_defs.md#networkinterfaceattachmentchangestypedef)
- `Description`: [AttributeValueTypeDef](./type_defs.md#attributevaluetypedef)
- `DryRun`: `bool`
- `Groups`: `Sequence`\[`str`\]
- `SourceDestCheck`:
  [AttributeBooleanValueTypeDef](./type_defs.md#attributebooleanvaluetypedef)

<a id="modify_private_dns_name_options"></a>

### modify_private_dns_name_options

Modifies the options for instance hostnames for the specified instance.

Type annotations for
`aiobotocore.create_client("ec2").modify_private_dns_name_options` method.

Boto3 documentation:
[EC2.Client.modify_private_dns_name_options](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_private_dns_name_options)

Asynchronous method. Use `await modify_private_dns_name_options(...)` for a
synchronous call.

Arguments mapping described in
[ModifyPrivateDnsNameOptionsRequestRequestTypeDef](./type_defs.md#modifyprivatednsnameoptionsrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `InstanceId`: `str`
- `PrivateDnsHostnameType`: [HostnameTypeType](./literals.md#hostnametypetype)
- `EnableResourceNameDnsARecord`: `bool`
- `EnableResourceNameDnsAAAARecord`: `bool`

Returns a `Coroutine` for
[ModifyPrivateDnsNameOptionsResultTypeDef](./type_defs.md#modifyprivatednsnameoptionsresulttypedef).

<a id="modify_reserved_instances"></a>

### modify_reserved_instances

Modifies the Availability Zone, instance count, instance type, or network
platform (EC2-Classic or EC2-VPC) of your Reserved Instances.

Type annotations for
`aiobotocore.create_client("ec2").modify_reserved_instances` method.

Boto3 documentation:
[EC2.Client.modify_reserved_instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_reserved_instances)

Asynchronous method. Use `await modify_reserved_instances(...)` for a
synchronous call.

Arguments mapping described in
[ModifyReservedInstancesRequestRequestTypeDef](./type_defs.md#modifyreservedinstancesrequestrequesttypedef).

Keyword-only arguments:

- `ReservedInstancesIds`: `Sequence`\[`str`\] *(required)*
- `TargetConfigurations`:
  `Sequence`\[[ReservedInstancesConfigurationTypeDef](./type_defs.md#reservedinstancesconfigurationtypedef)\]
  *(required)*
- `ClientToken`: `str`

Returns a `Coroutine` for
[ModifyReservedInstancesResultTypeDef](./type_defs.md#modifyreservedinstancesresulttypedef).

<a id="modify_security_group_rules"></a>

### modify_security_group_rules

Modifies the rules of a security group.

Type annotations for
`aiobotocore.create_client("ec2").modify_security_group_rules` method.

Boto3 documentation:
[EC2.Client.modify_security_group_rules](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_security_group_rules)

Asynchronous method. Use `await modify_security_group_rules(...)` for a
synchronous call.

Arguments mapping described in
[ModifySecurityGroupRulesRequestRequestTypeDef](./type_defs.md#modifysecuritygrouprulesrequestrequesttypedef).

Keyword-only arguments:

- `GroupId`: `str` *(required)*
- `SecurityGroupRules`:
  `Sequence`\[[SecurityGroupRuleUpdateTypeDef](./type_defs.md#securitygroupruleupdatetypedef)\]
  *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[ModifySecurityGroupRulesResultTypeDef](./type_defs.md#modifysecuritygrouprulesresulttypedef).

<a id="modify_snapshot_attribute"></a>

### modify_snapshot_attribute

Adds or removes permission settings for the specified snapshot.

Type annotations for
`aiobotocore.create_client("ec2").modify_snapshot_attribute` method.

Boto3 documentation:
[EC2.Client.modify_snapshot_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_snapshot_attribute)

Asynchronous method. Use `await modify_snapshot_attribute(...)` for a
synchronous call.

Arguments mapping described in
[ModifySnapshotAttributeRequestRequestTypeDef](./type_defs.md#modifysnapshotattributerequestrequesttypedef).

Keyword-only arguments:

- `SnapshotId`: `str` *(required)*
- `Attribute`:
  [SnapshotAttributeNameType](./literals.md#snapshotattributenametype)
- `CreateVolumePermission`:
  [CreateVolumePermissionModificationsTypeDef](./type_defs.md#createvolumepermissionmodificationstypedef)
- `GroupNames`: `Sequence`\[`str`\]
- `OperationType`: [OperationTypeType](./literals.md#operationtypetype)
- `UserIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`

<a id="modify_snapshot_tier"></a>

### modify_snapshot_tier

Archives an Amazon EBS snapshot.

Type annotations for `aiobotocore.create_client("ec2").modify_snapshot_tier`
method.

Boto3 documentation:
[EC2.Client.modify_snapshot_tier](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_snapshot_tier)

Asynchronous method. Use `await modify_snapshot_tier(...)` for a synchronous
call.

Arguments mapping described in
[ModifySnapshotTierRequestRequestTypeDef](./type_defs.md#modifysnapshottierrequestrequesttypedef).

Keyword-only arguments:

- `SnapshotId`: `str` *(required)*
- `StorageTier`: `Literal['archive']` (see
  [TargetStorageTierType](./literals.md#targetstoragetiertype))
- `DryRun`: `bool`

Returns a `Coroutine` for
[ModifySnapshotTierResultTypeDef](./type_defs.md#modifysnapshottierresulttypedef).

<a id="modify_spot_fleet_request"></a>

### modify_spot_fleet_request

Modifies the specified Spot Fleet request.

Type annotations for
`aiobotocore.create_client("ec2").modify_spot_fleet_request` method.

Boto3 documentation:
[EC2.Client.modify_spot_fleet_request](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_spot_fleet_request)

Asynchronous method. Use `await modify_spot_fleet_request(...)` for a
synchronous call.

Arguments mapping described in
[ModifySpotFleetRequestRequestRequestTypeDef](./type_defs.md#modifyspotfleetrequestrequestrequesttypedef).

Keyword-only arguments:

- `SpotFleetRequestId`: `str` *(required)*
- `ExcessCapacityTerminationPolicy`:
  [ExcessCapacityTerminationPolicyType](./literals.md#excesscapacityterminationpolicytype)
- `LaunchTemplateConfigs`:
  `Sequence`\[[LaunchTemplateConfigTypeDef](./type_defs.md#launchtemplateconfigtypedef)\]
- `TargetCapacity`: `int`
- `OnDemandTargetCapacity`: `int`
- `Context`: `str`

Returns a `Coroutine` for
[ModifySpotFleetRequestResponseTypeDef](./type_defs.md#modifyspotfleetrequestresponsetypedef).

<a id="modify_subnet_attribute"></a>

### modify_subnet_attribute

Modifies a subnet attribute.

Type annotations for `aiobotocore.create_client("ec2").modify_subnet_attribute`
method.

Boto3 documentation:
[EC2.Client.modify_subnet_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_subnet_attribute)

Asynchronous method. Use `await modify_subnet_attribute(...)` for a synchronous
call.

Arguments mapping described in
[ModifySubnetAttributeRequestRequestTypeDef](./type_defs.md#modifysubnetattributerequestrequesttypedef).

Keyword-only arguments:

- `SubnetId`: `str` *(required)*
- `AssignIpv6AddressOnCreation`:
  [AttributeBooleanValueTypeDef](./type_defs.md#attributebooleanvaluetypedef)
- `MapPublicIpOnLaunch`:
  [AttributeBooleanValueTypeDef](./type_defs.md#attributebooleanvaluetypedef)
- `MapCustomerOwnedIpOnLaunch`:
  [AttributeBooleanValueTypeDef](./type_defs.md#attributebooleanvaluetypedef)
- `CustomerOwnedIpv4Pool`: `str`
- `EnableDns64`:
  [AttributeBooleanValueTypeDef](./type_defs.md#attributebooleanvaluetypedef)
- `PrivateDnsHostnameTypeOnLaunch`:
  [HostnameTypeType](./literals.md#hostnametypetype)
- `EnableResourceNameDnsARecordOnLaunch`:
  [AttributeBooleanValueTypeDef](./type_defs.md#attributebooleanvaluetypedef)
- `EnableResourceNameDnsAAAARecordOnLaunch`:
  [AttributeBooleanValueTypeDef](./type_defs.md#attributebooleanvaluetypedef)
- `EnableLniAtDeviceIndex`: `int`
- `DisableLniAtDeviceIndex`:
  [AttributeBooleanValueTypeDef](./type_defs.md#attributebooleanvaluetypedef)

<a id="modify_traffic_mirror_filter_network_services"></a>

### modify_traffic_mirror_filter_network_services

Allows or restricts mirroring network services.

Type annotations for
`aiobotocore.create_client("ec2").modify_traffic_mirror_filter_network_services`
method.

Boto3 documentation:
[EC2.Client.modify_traffic_mirror_filter_network_services](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_traffic_mirror_filter_network_services)

Asynchronous method. Use
`await modify_traffic_mirror_filter_network_services(...)` for a synchronous
call.

Arguments mapping described in
[ModifyTrafficMirrorFilterNetworkServicesRequestRequestTypeDef](./type_defs.md#modifytrafficmirrorfilternetworkservicesrequestrequesttypedef).

Keyword-only arguments:

- `TrafficMirrorFilterId`: `str` *(required)*
- `AddNetworkServices`: `Sequence`\[`Literal['amazon-dns']` (see
  [TrafficMirrorNetworkServiceType](./literals.md#trafficmirrornetworkservicetype))\]
- `RemoveNetworkServices`: `Sequence`\[`Literal['amazon-dns']` (see
  [TrafficMirrorNetworkServiceType](./literals.md#trafficmirrornetworkservicetype))\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[ModifyTrafficMirrorFilterNetworkServicesResultTypeDef](./type_defs.md#modifytrafficmirrorfilternetworkservicesresulttypedef).

<a id="modify_traffic_mirror_filter_rule"></a>

### modify_traffic_mirror_filter_rule

Modifies the specified Traffic Mirror rule.

Type annotations for
`aiobotocore.create_client("ec2").modify_traffic_mirror_filter_rule` method.

Boto3 documentation:
[EC2.Client.modify_traffic_mirror_filter_rule](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_traffic_mirror_filter_rule)

Asynchronous method. Use `await modify_traffic_mirror_filter_rule(...)` for a
synchronous call.

Arguments mapping described in
[ModifyTrafficMirrorFilterRuleRequestRequestTypeDef](./type_defs.md#modifytrafficmirrorfilterrulerequestrequesttypedef).

Keyword-only arguments:

- `TrafficMirrorFilterRuleId`: `str` *(required)*
- `TrafficDirection`:
  [TrafficDirectionType](./literals.md#trafficdirectiontype)
- `RuleNumber`: `int`
- `RuleAction`:
  [TrafficMirrorRuleActionType](./literals.md#trafficmirrorruleactiontype)
- `DestinationPortRange`:
  [TrafficMirrorPortRangeRequestTypeDef](./type_defs.md#trafficmirrorportrangerequesttypedef)
- `SourcePortRange`:
  [TrafficMirrorPortRangeRequestTypeDef](./type_defs.md#trafficmirrorportrangerequesttypedef)
- `Protocol`: `int`
- `DestinationCidrBlock`: `str`
- `SourceCidrBlock`: `str`
- `Description`: `str`
- `RemoveFields`:
  `Sequence`\[[TrafficMirrorFilterRuleFieldType](./literals.md#trafficmirrorfilterrulefieldtype)\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[ModifyTrafficMirrorFilterRuleResultTypeDef](./type_defs.md#modifytrafficmirrorfilterruleresulttypedef).

<a id="modify_traffic_mirror_session"></a>

### modify_traffic_mirror_session

Modifies a Traffic Mirror session.

Type annotations for
`aiobotocore.create_client("ec2").modify_traffic_mirror_session` method.

Boto3 documentation:
[EC2.Client.modify_traffic_mirror_session](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_traffic_mirror_session)

Asynchronous method. Use `await modify_traffic_mirror_session(...)` for a
synchronous call.

Arguments mapping described in
[ModifyTrafficMirrorSessionRequestRequestTypeDef](./type_defs.md#modifytrafficmirrorsessionrequestrequesttypedef).

Keyword-only arguments:

- `TrafficMirrorSessionId`: `str` *(required)*
- `TrafficMirrorTargetId`: `str`
- `TrafficMirrorFilterId`: `str`
- `PacketLength`: `int`
- `SessionNumber`: `int`
- `VirtualNetworkId`: `int`
- `Description`: `str`
- `RemoveFields`:
  `Sequence`\[[TrafficMirrorSessionFieldType](./literals.md#trafficmirrorsessionfieldtype)\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[ModifyTrafficMirrorSessionResultTypeDef](./type_defs.md#modifytrafficmirrorsessionresulttypedef).

<a id="modify_transit_gateway"></a>

### modify_transit_gateway

Modifies the specified transit gateway.

Type annotations for `aiobotocore.create_client("ec2").modify_transit_gateway`
method.

Boto3 documentation:
[EC2.Client.modify_transit_gateway](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_transit_gateway)

Asynchronous method. Use `await modify_transit_gateway(...)` for a synchronous
call.

Arguments mapping described in
[ModifyTransitGatewayRequestRequestTypeDef](./type_defs.md#modifytransitgatewayrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayId`: `str` *(required)*
- `Description`: `str`
- `Options`:
  [ModifyTransitGatewayOptionsTypeDef](./type_defs.md#modifytransitgatewayoptionstypedef)
- `DryRun`: `bool`

Returns a `Coroutine` for
[ModifyTransitGatewayResultTypeDef](./type_defs.md#modifytransitgatewayresulttypedef).

<a id="modify_transit_gateway_prefix_list_reference"></a>

### modify_transit_gateway_prefix_list_reference

Modifies a reference (route) to a prefix list in a specified transit gateway
route table.

Type annotations for
`aiobotocore.create_client("ec2").modify_transit_gateway_prefix_list_reference`
method.

Boto3 documentation:
[EC2.Client.modify_transit_gateway_prefix_list_reference](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_transit_gateway_prefix_list_reference)

Asynchronous method. Use
`await modify_transit_gateway_prefix_list_reference(...)` for a synchronous
call.

Arguments mapping described in
[ModifyTransitGatewayPrefixListReferenceRequestRequestTypeDef](./type_defs.md#modifytransitgatewayprefixlistreferencerequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayRouteTableId`: `str` *(required)*
- `PrefixListId`: `str` *(required)*
- `TransitGatewayAttachmentId`: `str`
- `Blackhole`: `bool`
- `DryRun`: `bool`

Returns a `Coroutine` for
[ModifyTransitGatewayPrefixListReferenceResultTypeDef](./type_defs.md#modifytransitgatewayprefixlistreferenceresulttypedef).

<a id="modify_transit_gateway_vpc_attachment"></a>

### modify_transit_gateway_vpc_attachment

Modifies the specified VPC attachment.

Type annotations for
`aiobotocore.create_client("ec2").modify_transit_gateway_vpc_attachment`
method.

Boto3 documentation:
[EC2.Client.modify_transit_gateway_vpc_attachment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_transit_gateway_vpc_attachment)

Asynchronous method. Use `await modify_transit_gateway_vpc_attachment(...)` for
a synchronous call.

Arguments mapping described in
[ModifyTransitGatewayVpcAttachmentRequestRequestTypeDef](./type_defs.md#modifytransitgatewayvpcattachmentrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayAttachmentId`: `str` *(required)*
- `AddSubnetIds`: `Sequence`\[`str`\]
- `RemoveSubnetIds`: `Sequence`\[`str`\]
- `Options`:
  [ModifyTransitGatewayVpcAttachmentRequestOptionsTypeDef](./type_defs.md#modifytransitgatewayvpcattachmentrequestoptionstypedef)
- `DryRun`: `bool`

Returns a `Coroutine` for
[ModifyTransitGatewayVpcAttachmentResultTypeDef](./type_defs.md#modifytransitgatewayvpcattachmentresulttypedef).

<a id="modify_volume"></a>

### modify_volume

You can modify several parameters of an existing EBS volume, including volume
size, volume type, and IOPS capacity.

Type annotations for `aiobotocore.create_client("ec2").modify_volume` method.

Boto3 documentation:
[EC2.Client.modify_volume](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_volume)

Asynchronous method. Use `await modify_volume(...)` for a synchronous call.

Arguments mapping described in
[ModifyVolumeRequestRequestTypeDef](./type_defs.md#modifyvolumerequestrequesttypedef).

Keyword-only arguments:

- `VolumeId`: `str` *(required)*
- `DryRun`: `bool`
- `Size`: `int`
- `VolumeType`: [VolumeTypeType](./literals.md#volumetypetype)
- `Iops`: `int`
- `Throughput`: `int`
- `MultiAttachEnabled`: `bool`

Returns a `Coroutine` for
[ModifyVolumeResultTypeDef](./type_defs.md#modifyvolumeresulttypedef).

<a id="modify_volume_attribute"></a>

### modify_volume_attribute

Modifies a volume attribute.

Type annotations for `aiobotocore.create_client("ec2").modify_volume_attribute`
method.

Boto3 documentation:
[EC2.Client.modify_volume_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_volume_attribute)

Asynchronous method. Use `await modify_volume_attribute(...)` for a synchronous
call.

Arguments mapping described in
[ModifyVolumeAttributeRequestRequestTypeDef](./type_defs.md#modifyvolumeattributerequestrequesttypedef).

Keyword-only arguments:

- `VolumeId`: `str` *(required)*
- `AutoEnableIO`:
  [AttributeBooleanValueTypeDef](./type_defs.md#attributebooleanvaluetypedef)
- `DryRun`: `bool`

<a id="modify_vpc_attribute"></a>

### modify_vpc_attribute

Modifies the specified attribute of the specified VPC.

Type annotations for `aiobotocore.create_client("ec2").modify_vpc_attribute`
method.

Boto3 documentation:
[EC2.Client.modify_vpc_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_vpc_attribute)

Asynchronous method. Use `await modify_vpc_attribute(...)` for a synchronous
call.

Arguments mapping described in
[ModifyVpcAttributeRequestRequestTypeDef](./type_defs.md#modifyvpcattributerequestrequesttypedef).

Keyword-only arguments:

- `VpcId`: `str` *(required)*
- `EnableDnsHostnames`:
  [AttributeBooleanValueTypeDef](./type_defs.md#attributebooleanvaluetypedef)
- `EnableDnsSupport`:
  [AttributeBooleanValueTypeDef](./type_defs.md#attributebooleanvaluetypedef)

<a id="modify_vpc_endpoint"></a>

### modify_vpc_endpoint

Modifies attributes of a specified VPC endpoint.

Type annotations for `aiobotocore.create_client("ec2").modify_vpc_endpoint`
method.

Boto3 documentation:
[EC2.Client.modify_vpc_endpoint](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_vpc_endpoint)

Asynchronous method. Use `await modify_vpc_endpoint(...)` for a synchronous
call.

Arguments mapping described in
[ModifyVpcEndpointRequestRequestTypeDef](./type_defs.md#modifyvpcendpointrequestrequesttypedef).

Keyword-only arguments:

- `VpcEndpointId`: `str` *(required)*
- `DryRun`: `bool`
- `ResetPolicy`: `bool`
- `PolicyDocument`: `str`
- `AddRouteTableIds`: `Sequence`\[`str`\]
- `RemoveRouteTableIds`: `Sequence`\[`str`\]
- `AddSubnetIds`: `Sequence`\[`str`\]
- `RemoveSubnetIds`: `Sequence`\[`str`\]
- `AddSecurityGroupIds`: `Sequence`\[`str`\]
- `RemoveSecurityGroupIds`: `Sequence`\[`str`\]
- `PrivateDnsEnabled`: `bool`

Returns a `Coroutine` for
[ModifyVpcEndpointResultTypeDef](./type_defs.md#modifyvpcendpointresulttypedef).

<a id="modify_vpc_endpoint_connection_notification"></a>

### modify_vpc_endpoint_connection_notification

Modifies a connection notification for VPC endpoint or VPC endpoint service.

Type annotations for
`aiobotocore.create_client("ec2").modify_vpc_endpoint_connection_notification`
method.

Boto3 documentation:
[EC2.Client.modify_vpc_endpoint_connection_notification](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_vpc_endpoint_connection_notification)

Asynchronous method. Use
`await modify_vpc_endpoint_connection_notification(...)` for a synchronous
call.

Arguments mapping described in
[ModifyVpcEndpointConnectionNotificationRequestRequestTypeDef](./type_defs.md#modifyvpcendpointconnectionnotificationrequestrequesttypedef).

Keyword-only arguments:

- `ConnectionNotificationId`: `str` *(required)*
- `DryRun`: `bool`
- `ConnectionNotificationArn`: `str`
- `ConnectionEvents`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[ModifyVpcEndpointConnectionNotificationResultTypeDef](./type_defs.md#modifyvpcendpointconnectionnotificationresulttypedef).

<a id="modify_vpc_endpoint_service_configuration"></a>

### modify_vpc_endpoint_service_configuration

Modifies the attributes of your VPC endpoint service configuration.

Type annotations for
`aiobotocore.create_client("ec2").modify_vpc_endpoint_service_configuration`
method.

Boto3 documentation:
[EC2.Client.modify_vpc_endpoint_service_configuration](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_vpc_endpoint_service_configuration)

Asynchronous method. Use `await modify_vpc_endpoint_service_configuration(...)`
for a synchronous call.

Arguments mapping described in
[ModifyVpcEndpointServiceConfigurationRequestRequestTypeDef](./type_defs.md#modifyvpcendpointserviceconfigurationrequestrequesttypedef).

Keyword-only arguments:

- `ServiceId`: `str` *(required)*
- `DryRun`: `bool`
- `PrivateDnsName`: `str`
- `RemovePrivateDnsName`: `bool`
- `AcceptanceRequired`: `bool`
- `AddNetworkLoadBalancerArns`: `Sequence`\[`str`\]
- `RemoveNetworkLoadBalancerArns`: `Sequence`\[`str`\]
- `AddGatewayLoadBalancerArns`: `Sequence`\[`str`\]
- `RemoveGatewayLoadBalancerArns`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[ModifyVpcEndpointServiceConfigurationResultTypeDef](./type_defs.md#modifyvpcendpointserviceconfigurationresulttypedef).

<a id="modify_vpc_endpoint_service_permissions"></a>

### modify_vpc_endpoint_service_permissions

Modifies the permissions for your \[VPC endpoint
service\](https://docs.aws.amazon.com/vpc/latest/userguide/endpoint-
service.html)\_.

Type annotations for
`aiobotocore.create_client("ec2").modify_vpc_endpoint_service_permissions`
method.

Boto3 documentation:
[EC2.Client.modify_vpc_endpoint_service_permissions](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_vpc_endpoint_service_permissions)

Asynchronous method. Use `await modify_vpc_endpoint_service_permissions(...)`
for a synchronous call.

Arguments mapping described in
[ModifyVpcEndpointServicePermissionsRequestRequestTypeDef](./type_defs.md#modifyvpcendpointservicepermissionsrequestrequesttypedef).

Keyword-only arguments:

- `ServiceId`: `str` *(required)*
- `DryRun`: `bool`
- `AddAllowedPrincipals`: `Sequence`\[`str`\]
- `RemoveAllowedPrincipals`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[ModifyVpcEndpointServicePermissionsResultTypeDef](./type_defs.md#modifyvpcendpointservicepermissionsresulttypedef).

<a id="modify_vpc_peering_connection_options"></a>

### modify_vpc_peering_connection_options

Modifies the VPC peering connection options on one side of a VPC peering
connection.

Type annotations for
`aiobotocore.create_client("ec2").modify_vpc_peering_connection_options`
method.

Boto3 documentation:
[EC2.Client.modify_vpc_peering_connection_options](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_vpc_peering_connection_options)

Asynchronous method. Use `await modify_vpc_peering_connection_options(...)` for
a synchronous call.

Arguments mapping described in
[ModifyVpcPeeringConnectionOptionsRequestRequestTypeDef](./type_defs.md#modifyvpcpeeringconnectionoptionsrequestrequesttypedef).

Keyword-only arguments:

- `VpcPeeringConnectionId`: `str` *(required)*
- `AccepterPeeringConnectionOptions`:
  [PeeringConnectionOptionsRequestTypeDef](./type_defs.md#peeringconnectionoptionsrequesttypedef)
- `DryRun`: `bool`
- `RequesterPeeringConnectionOptions`:
  [PeeringConnectionOptionsRequestTypeDef](./type_defs.md#peeringconnectionoptionsrequesttypedef)

Returns a `Coroutine` for
[ModifyVpcPeeringConnectionOptionsResultTypeDef](./type_defs.md#modifyvpcpeeringconnectionoptionsresulttypedef).

<a id="modify_vpc_tenancy"></a>

### modify_vpc_tenancy

Modifies the instance tenancy attribute of the specified VPC.

Type annotations for `aiobotocore.create_client("ec2").modify_vpc_tenancy`
method.

Boto3 documentation:
[EC2.Client.modify_vpc_tenancy](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_vpc_tenancy)

Asynchronous method. Use `await modify_vpc_tenancy(...)` for a synchronous
call.

Arguments mapping described in
[ModifyVpcTenancyRequestRequestTypeDef](./type_defs.md#modifyvpctenancyrequestrequesttypedef).

Keyword-only arguments:

- `VpcId`: `str` *(required)*
- `InstanceTenancy`: `Literal['default']` (see
  [VpcTenancyType](./literals.md#vpctenancytype)) *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[ModifyVpcTenancyResultTypeDef](./type_defs.md#modifyvpctenancyresulttypedef).

<a id="modify_vpn_connection"></a>

### modify_vpn_connection

Modifies the customer gateway or the target gateway of an Amazon Web Services
Site-to-Site VPN connection.

Type annotations for `aiobotocore.create_client("ec2").modify_vpn_connection`
method.

Boto3 documentation:
[EC2.Client.modify_vpn_connection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_vpn_connection)

Asynchronous method. Use `await modify_vpn_connection(...)` for a synchronous
call.

Arguments mapping described in
[ModifyVpnConnectionRequestRequestTypeDef](./type_defs.md#modifyvpnconnectionrequestrequesttypedef).

Keyword-only arguments:

- `VpnConnectionId`: `str` *(required)*
- `TransitGatewayId`: `str`
- `CustomerGatewayId`: `str`
- `VpnGatewayId`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[ModifyVpnConnectionResultTypeDef](./type_defs.md#modifyvpnconnectionresulttypedef).

<a id="modify_vpn_connection_options"></a>

### modify_vpn_connection_options

Modifies the connection options for your Site-to-Site VPN connection.

Type annotations for
`aiobotocore.create_client("ec2").modify_vpn_connection_options` method.

Boto3 documentation:
[EC2.Client.modify_vpn_connection_options](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_vpn_connection_options)

Asynchronous method. Use `await modify_vpn_connection_options(...)` for a
synchronous call.

Arguments mapping described in
[ModifyVpnConnectionOptionsRequestRequestTypeDef](./type_defs.md#modifyvpnconnectionoptionsrequestrequesttypedef).

Keyword-only arguments:

- `VpnConnectionId`: `str` *(required)*
- `LocalIpv4NetworkCidr`: `str`
- `RemoteIpv4NetworkCidr`: `str`
- `LocalIpv6NetworkCidr`: `str`
- `RemoteIpv6NetworkCidr`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[ModifyVpnConnectionOptionsResultTypeDef](./type_defs.md#modifyvpnconnectionoptionsresulttypedef).

<a id="modify_vpn_tunnel_certificate"></a>

### modify_vpn_tunnel_certificate

Modifies the VPN tunnel endpoint certificate.

Type annotations for
`aiobotocore.create_client("ec2").modify_vpn_tunnel_certificate` method.

Boto3 documentation:
[EC2.Client.modify_vpn_tunnel_certificate](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_vpn_tunnel_certificate)

Asynchronous method. Use `await modify_vpn_tunnel_certificate(...)` for a
synchronous call.

Arguments mapping described in
[ModifyVpnTunnelCertificateRequestRequestTypeDef](./type_defs.md#modifyvpntunnelcertificaterequestrequesttypedef).

Keyword-only arguments:

- `VpnConnectionId`: `str` *(required)*
- `VpnTunnelOutsideIpAddress`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[ModifyVpnTunnelCertificateResultTypeDef](./type_defs.md#modifyvpntunnelcertificateresulttypedef).

<a id="modify_vpn_tunnel_options"></a>

### modify_vpn_tunnel_options

Modifies the options for a VPN tunnel in an Amazon Web Services Site-to-Site
VPN connection.

Type annotations for
`aiobotocore.create_client("ec2").modify_vpn_tunnel_options` method.

Boto3 documentation:
[EC2.Client.modify_vpn_tunnel_options](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.modify_vpn_tunnel_options)

Asynchronous method. Use `await modify_vpn_tunnel_options(...)` for a
synchronous call.

Arguments mapping described in
[ModifyVpnTunnelOptionsRequestRequestTypeDef](./type_defs.md#modifyvpntunneloptionsrequestrequesttypedef).

Keyword-only arguments:

- `VpnConnectionId`: `str` *(required)*
- `VpnTunnelOutsideIpAddress`: `str` *(required)*
- `TunnelOptions`:
  [ModifyVpnTunnelOptionsSpecificationTypeDef](./type_defs.md#modifyvpntunneloptionsspecificationtypedef)
  *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[ModifyVpnTunnelOptionsResultTypeDef](./type_defs.md#modifyvpntunneloptionsresulttypedef).

<a id="monitor_instances"></a>

### monitor_instances

Enables detailed monitoring for a running instance.

Type annotations for `aiobotocore.create_client("ec2").monitor_instances`
method.

Boto3 documentation:
[EC2.Client.monitor_instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.monitor_instances)

Asynchronous method. Use `await monitor_instances(...)` for a synchronous call.

Arguments mapping described in
[MonitorInstancesRequestRequestTypeDef](./type_defs.md#monitorinstancesrequestrequesttypedef).

Keyword-only arguments:

- `InstanceIds`: `Sequence`\[`str`\] *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[MonitorInstancesResultTypeDef](./type_defs.md#monitorinstancesresulttypedef).

<a id="move_address_to_vpc"></a>

### move_address_to_vpc

Moves an Elastic IP address from the EC2-Classic platform to the EC2-VPC
platform.

Type annotations for `aiobotocore.create_client("ec2").move_address_to_vpc`
method.

Boto3 documentation:
[EC2.Client.move_address_to_vpc](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.move_address_to_vpc)

Asynchronous method. Use `await move_address_to_vpc(...)` for a synchronous
call.

Arguments mapping described in
[MoveAddressToVpcRequestRequestTypeDef](./type_defs.md#moveaddresstovpcrequestrequesttypedef).

Keyword-only arguments:

- `PublicIp`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[MoveAddressToVpcResultTypeDef](./type_defs.md#moveaddresstovpcresulttypedef).

<a id="move_byoip_cidr_to_ipam"></a>

### move_byoip_cidr_to_ipam

Move an BYOIP IPv4 CIDR to IPAM from a public IPv4 pool.

Type annotations for `aiobotocore.create_client("ec2").move_byoip_cidr_to_ipam`
method.

Boto3 documentation:
[EC2.Client.move_byoip_cidr_to_ipam](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.move_byoip_cidr_to_ipam)

Asynchronous method. Use `await move_byoip_cidr_to_ipam(...)` for a synchronous
call.

Arguments mapping described in
[MoveByoipCidrToIpamRequestRequestTypeDef](./type_defs.md#movebyoipcidrtoipamrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `Cidr`: `str`
- `IpamPoolId`: `str`
- `IpamPoolOwner`: `str`

Returns a `Coroutine` for
[MoveByoipCidrToIpamResultTypeDef](./type_defs.md#movebyoipcidrtoipamresulttypedef).

<a id="provision_byoip_cidr"></a>

### provision_byoip_cidr

Provisions an IPv4 or IPv6 address range for use with your Amazon Web Services
resources through bring your own IP addresses (BYOIP) and creates a
corresponding address pool.

Type annotations for `aiobotocore.create_client("ec2").provision_byoip_cidr`
method.

Boto3 documentation:
[EC2.Client.provision_byoip_cidr](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.provision_byoip_cidr)

Asynchronous method. Use `await provision_byoip_cidr(...)` for a synchronous
call.

Arguments mapping described in
[ProvisionByoipCidrRequestRequestTypeDef](./type_defs.md#provisionbyoipcidrrequestrequesttypedef).

Keyword-only arguments:

- `Cidr`: `str` *(required)*
- `CidrAuthorizationContext`:
  [CidrAuthorizationContextTypeDef](./type_defs.md#cidrauthorizationcontexttypedef)
- `PubliclyAdvertisable`: `bool`
- `Description`: `str`
- `DryRun`: `bool`
- `PoolTagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `MultiRegion`: `bool`

Returns a `Coroutine` for
[ProvisionByoipCidrResultTypeDef](./type_defs.md#provisionbyoipcidrresulttypedef).

<a id="provision_ipam_pool_cidr"></a>

### provision_ipam_pool_cidr

Provision a CIDR to an IPAM pool.

Type annotations for
`aiobotocore.create_client("ec2").provision_ipam_pool_cidr` method.

Boto3 documentation:
[EC2.Client.provision_ipam_pool_cidr](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.provision_ipam_pool_cidr)

Asynchronous method. Use `await provision_ipam_pool_cidr(...)` for a
synchronous call.

Arguments mapping described in
[ProvisionIpamPoolCidrRequestRequestTypeDef](./type_defs.md#provisionipampoolcidrrequestrequesttypedef).

Keyword-only arguments:

- `IpamPoolId`: `str` *(required)*
- `DryRun`: `bool`
- `Cidr`: `str`
- `CidrAuthorizationContext`:
  [IpamCidrAuthorizationContextTypeDef](./type_defs.md#ipamcidrauthorizationcontexttypedef)

Returns a `Coroutine` for
[ProvisionIpamPoolCidrResultTypeDef](./type_defs.md#provisionipampoolcidrresulttypedef).

<a id="provision_public_ipv4_pool_cidr"></a>

### provision_public_ipv4_pool_cidr

Provision a CIDR to a public IPv4 pool.

Type annotations for
`aiobotocore.create_client("ec2").provision_public_ipv4_pool_cidr` method.

Boto3 documentation:
[EC2.Client.provision_public_ipv4_pool_cidr](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.provision_public_ipv4_pool_cidr)

Asynchronous method. Use `await provision_public_ipv4_pool_cidr(...)` for a
synchronous call.

Arguments mapping described in
[ProvisionPublicIpv4PoolCidrRequestRequestTypeDef](./type_defs.md#provisionpublicipv4poolcidrrequestrequesttypedef).

Keyword-only arguments:

- `IpamPoolId`: `str` *(required)*
- `PoolId`: `str` *(required)*
- `NetmaskLength`: `int` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[ProvisionPublicIpv4PoolCidrResultTypeDef](./type_defs.md#provisionpublicipv4poolcidrresulttypedef).

<a id="purchase_host_reservation"></a>

### purchase_host_reservation

Purchase a reservation with configurations that match those of your Dedicated
Host.

Type annotations for
`aiobotocore.create_client("ec2").purchase_host_reservation` method.

Boto3 documentation:
[EC2.Client.purchase_host_reservation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.purchase_host_reservation)

Asynchronous method. Use `await purchase_host_reservation(...)` for a
synchronous call.

Arguments mapping described in
[PurchaseHostReservationRequestRequestTypeDef](./type_defs.md#purchasehostreservationrequestrequesttypedef).

Keyword-only arguments:

- `HostIdSet`: `Sequence`\[`str`\] *(required)*
- `OfferingId`: `str` *(required)*
- `ClientToken`: `str`
- `CurrencyCode`: `Literal['USD']` (see
  [CurrencyCodeValuesType](./literals.md#currencycodevaluestype))
- `LimitPrice`: `str`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for
[PurchaseHostReservationResultTypeDef](./type_defs.md#purchasehostreservationresulttypedef).

<a id="purchase_reserved_instances_offering"></a>

### purchase_reserved_instances_offering

Purchases a Reserved Instance for use with your account.

Type annotations for
`aiobotocore.create_client("ec2").purchase_reserved_instances_offering` method.

Boto3 documentation:
[EC2.Client.purchase_reserved_instances_offering](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.purchase_reserved_instances_offering)

Asynchronous method. Use `await purchase_reserved_instances_offering(...)` for
a synchronous call.

Arguments mapping described in
[PurchaseReservedInstancesOfferingRequestRequestTypeDef](./type_defs.md#purchasereservedinstancesofferingrequestrequesttypedef).

Keyword-only arguments:

- `InstanceCount`: `int` *(required)*
- `ReservedInstancesOfferingId`: `str` *(required)*
- `DryRun`: `bool`
- `LimitPrice`:
  [ReservedInstanceLimitPriceTypeDef](./type_defs.md#reservedinstancelimitpricetypedef)
- `PurchaseTime`: `Union`\[`datetime`, `str`\]

Returns a `Coroutine` for
[PurchaseReservedInstancesOfferingResultTypeDef](./type_defs.md#purchasereservedinstancesofferingresulttypedef).

<a id="purchase_scheduled_instances"></a>

### purchase_scheduled_instances

Purchases the Scheduled Instances with the specified schedule.

Type annotations for
`aiobotocore.create_client("ec2").purchase_scheduled_instances` method.

Boto3 documentation:
[EC2.Client.purchase_scheduled_instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.purchase_scheduled_instances)

Asynchronous method. Use `await purchase_scheduled_instances(...)` for a
synchronous call.

Arguments mapping described in
[PurchaseScheduledInstancesRequestRequestTypeDef](./type_defs.md#purchasescheduledinstancesrequestrequesttypedef).

Keyword-only arguments:

- `PurchaseRequests`:
  `Sequence`\[[PurchaseRequestTypeDef](./type_defs.md#purchaserequesttypedef)\]
  *(required)*
- `ClientToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[PurchaseScheduledInstancesResultTypeDef](./type_defs.md#purchasescheduledinstancesresulttypedef).

<a id="reboot_instances"></a>

### reboot_instances

Requests a reboot of the specified instances.

Type annotations for `aiobotocore.create_client("ec2").reboot_instances`
method.

Boto3 documentation:
[EC2.Client.reboot_instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.reboot_instances)

Asynchronous method. Use `await reboot_instances(...)` for a synchronous call.

Arguments mapping described in
[RebootInstancesRequestRequestTypeDef](./type_defs.md#rebootinstancesrequestrequesttypedef).

Keyword-only arguments:

- `InstanceIds`: `Sequence`\[`str`\] *(required)*
- `DryRun`: `bool`

<a id="register_image"></a>

### register_image

Registers an AMI.

Type annotations for `aiobotocore.create_client("ec2").register_image` method.

Boto3 documentation:
[EC2.Client.register_image](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.register_image)

Asynchronous method. Use `await register_image(...)` for a synchronous call.

Arguments mapping described in
[RegisterImageRequestRequestTypeDef](./type_defs.md#registerimagerequestrequesttypedef).

Keyword-only arguments:

- `Name`: `str` *(required)*
- `ImageLocation`: `str`
- `Architecture`:
  [ArchitectureValuesType](./literals.md#architecturevaluestype)
- `BlockDeviceMappings`:
  `Sequence`\[[BlockDeviceMappingTypeDef](./type_defs.md#blockdevicemappingtypedef)\]
- `Description`: `str`
- `DryRun`: `bool`
- `EnaSupport`: `bool`
- `KernelId`: `str`
- `BillingProducts`: `Sequence`\[`str`\]
- `RamdiskId`: `str`
- `RootDeviceName`: `str`
- `SriovNetSupport`: `str`
- `VirtualizationType`: `str`
- `BootMode`: [BootModeValuesType](./literals.md#bootmodevaluestype)

Returns a `Coroutine` for
[RegisterImageResultTypeDef](./type_defs.md#registerimageresulttypedef).

<a id="register_instance_event_notification_attributes"></a>

### register_instance_event_notification_attributes

Registers a set of tag keys to include in scheduled event notifications for
your resources.

Type annotations for
`aiobotocore.create_client("ec2").register_instance_event_notification_attributes`
method.

Boto3 documentation:
[EC2.Client.register_instance_event_notification_attributes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.register_instance_event_notification_attributes)

Asynchronous method. Use
`await register_instance_event_notification_attributes(...)` for a synchronous
call.

Arguments mapping described in
[RegisterInstanceEventNotificationAttributesRequestRequestTypeDef](./type_defs.md#registerinstanceeventnotificationattributesrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `InstanceTagAttribute`:
  [RegisterInstanceTagAttributeRequestTypeDef](./type_defs.md#registerinstancetagattributerequesttypedef)

Returns a `Coroutine` for
[RegisterInstanceEventNotificationAttributesResultTypeDef](./type_defs.md#registerinstanceeventnotificationattributesresulttypedef).

<a id="register_transit_gateway_multicast_group_members"></a>

### register_transit_gateway_multicast_group_members

Registers members (network interfaces) with the transit gateway multicast
group.

Type annotations for
`aiobotocore.create_client("ec2").register_transit_gateway_multicast_group_members`
method.

Boto3 documentation:
[EC2.Client.register_transit_gateway_multicast_group_members](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.register_transit_gateway_multicast_group_members)

Asynchronous method. Use
`await register_transit_gateway_multicast_group_members(...)` for a synchronous
call.

Arguments mapping described in
[RegisterTransitGatewayMulticastGroupMembersRequestRequestTypeDef](./type_defs.md#registertransitgatewaymulticastgroupmembersrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayMulticastDomainId`: `str`
- `GroupIpAddress`: `str`
- `NetworkInterfaceIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[RegisterTransitGatewayMulticastGroupMembersResultTypeDef](./type_defs.md#registertransitgatewaymulticastgroupmembersresulttypedef).

<a id="register_transit_gateway_multicast_group_sources"></a>

### register_transit_gateway_multicast_group_sources

Registers sources (network interfaces) with the specified transit gateway
multicast group.

Type annotations for
`aiobotocore.create_client("ec2").register_transit_gateway_multicast_group_sources`
method.

Boto3 documentation:
[EC2.Client.register_transit_gateway_multicast_group_sources](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.register_transit_gateway_multicast_group_sources)

Asynchronous method. Use
`await register_transit_gateway_multicast_group_sources(...)` for a synchronous
call.

Arguments mapping described in
[RegisterTransitGatewayMulticastGroupSourcesRequestRequestTypeDef](./type_defs.md#registertransitgatewaymulticastgroupsourcesrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayMulticastDomainId`: `str`
- `GroupIpAddress`: `str`
- `NetworkInterfaceIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[RegisterTransitGatewayMulticastGroupSourcesResultTypeDef](./type_defs.md#registertransitgatewaymulticastgroupsourcesresulttypedef).

<a id="reject_transit_gateway_multicast_domain_associations"></a>

### reject_transit_gateway_multicast_domain_associations

Rejects a request to associate cross-account subnets with a transit gateway
multicast domain.

Type annotations for
`aiobotocore.create_client("ec2").reject_transit_gateway_multicast_domain_associations`
method.

Boto3 documentation:
[EC2.Client.reject_transit_gateway_multicast_domain_associations](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.reject_transit_gateway_multicast_domain_associations)

Asynchronous method. Use
`await reject_transit_gateway_multicast_domain_associations(...)` for a
synchronous call.

Arguments mapping described in
[RejectTransitGatewayMulticastDomainAssociationsRequestRequestTypeDef](./type_defs.md#rejecttransitgatewaymulticastdomainassociationsrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayMulticastDomainId`: `str`
- `TransitGatewayAttachmentId`: `str`
- `SubnetIds`: `Sequence`\[`str`\]
- `DryRun`: `bool`

Returns a `Coroutine` for
[RejectTransitGatewayMulticastDomainAssociationsResultTypeDef](./type_defs.md#rejecttransitgatewaymulticastdomainassociationsresulttypedef).

<a id="reject_transit_gateway_peering_attachment"></a>

### reject_transit_gateway_peering_attachment

Rejects a transit gateway peering attachment request.

Type annotations for
`aiobotocore.create_client("ec2").reject_transit_gateway_peering_attachment`
method.

Boto3 documentation:
[EC2.Client.reject_transit_gateway_peering_attachment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.reject_transit_gateway_peering_attachment)

Asynchronous method. Use `await reject_transit_gateway_peering_attachment(...)`
for a synchronous call.

Arguments mapping described in
[RejectTransitGatewayPeeringAttachmentRequestRequestTypeDef](./type_defs.md#rejecttransitgatewaypeeringattachmentrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayAttachmentId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[RejectTransitGatewayPeeringAttachmentResultTypeDef](./type_defs.md#rejecttransitgatewaypeeringattachmentresulttypedef).

<a id="reject_transit_gateway_vpc_attachment"></a>

### reject_transit_gateway_vpc_attachment

Rejects a request to attach a VPC to a transit gateway.

Type annotations for
`aiobotocore.create_client("ec2").reject_transit_gateway_vpc_attachment`
method.

Boto3 documentation:
[EC2.Client.reject_transit_gateway_vpc_attachment](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.reject_transit_gateway_vpc_attachment)

Asynchronous method. Use `await reject_transit_gateway_vpc_attachment(...)` for
a synchronous call.

Arguments mapping described in
[RejectTransitGatewayVpcAttachmentRequestRequestTypeDef](./type_defs.md#rejecttransitgatewayvpcattachmentrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayAttachmentId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[RejectTransitGatewayVpcAttachmentResultTypeDef](./type_defs.md#rejecttransitgatewayvpcattachmentresulttypedef).

<a id="reject_vpc_endpoint_connections"></a>

### reject_vpc_endpoint_connections

Rejects one or more VPC endpoint connection requests to your VPC endpoint
service.

Type annotations for
`aiobotocore.create_client("ec2").reject_vpc_endpoint_connections` method.

Boto3 documentation:
[EC2.Client.reject_vpc_endpoint_connections](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.reject_vpc_endpoint_connections)

Asynchronous method. Use `await reject_vpc_endpoint_connections(...)` for a
synchronous call.

Arguments mapping described in
[RejectVpcEndpointConnectionsRequestRequestTypeDef](./type_defs.md#rejectvpcendpointconnectionsrequestrequesttypedef).

Keyword-only arguments:

- `ServiceId`: `str` *(required)*
- `VpcEndpointIds`: `Sequence`\[`str`\] *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[RejectVpcEndpointConnectionsResultTypeDef](./type_defs.md#rejectvpcendpointconnectionsresulttypedef).

<a id="reject_vpc_peering_connection"></a>

### reject_vpc_peering_connection

Rejects a VPC peering connection request.

Type annotations for
`aiobotocore.create_client("ec2").reject_vpc_peering_connection` method.

Boto3 documentation:
[EC2.Client.reject_vpc_peering_connection](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.reject_vpc_peering_connection)

Asynchronous method. Use `await reject_vpc_peering_connection(...)` for a
synchronous call.

Arguments mapping described in
[RejectVpcPeeringConnectionRequestRequestTypeDef](./type_defs.md#rejectvpcpeeringconnectionrequestrequesttypedef).

Keyword-only arguments:

- `VpcPeeringConnectionId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[RejectVpcPeeringConnectionResultTypeDef](./type_defs.md#rejectvpcpeeringconnectionresulttypedef).

<a id="release_address"></a>

### release_address

Releases the specified Elastic IP address.

Type annotations for `aiobotocore.create_client("ec2").release_address` method.

Boto3 documentation:
[EC2.Client.release_address](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.release_address)

Asynchronous method. Use `await release_address(...)` for a synchronous call.

Arguments mapping described in
[ReleaseAddressRequestRequestTypeDef](./type_defs.md#releaseaddressrequestrequesttypedef).

Keyword-only arguments:

- `AllocationId`: `str`
- `PublicIp`: `str`
- `NetworkBorderGroup`: `str`
- `DryRun`: `bool`

<a id="release_hosts"></a>

### release_hosts

When you no longer want to use an On-Demand Dedicated Host it can be released.

Type annotations for `aiobotocore.create_client("ec2").release_hosts` method.

Boto3 documentation:
[EC2.Client.release_hosts](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.release_hosts)

Asynchronous method. Use `await release_hosts(...)` for a synchronous call.

Arguments mapping described in
[ReleaseHostsRequestRequestTypeDef](./type_defs.md#releasehostsrequestrequesttypedef).

Keyword-only arguments:

- `HostIds`: `Sequence`\[`str`\] *(required)*

Returns a `Coroutine` for
[ReleaseHostsResultTypeDef](./type_defs.md#releasehostsresulttypedef).

<a id="release_ipam_pool_allocation"></a>

### release_ipam_pool_allocation

Release an allocation within an IPAM pool.

Type annotations for
`aiobotocore.create_client("ec2").release_ipam_pool_allocation` method.

Boto3 documentation:
[EC2.Client.release_ipam_pool_allocation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.release_ipam_pool_allocation)

Asynchronous method. Use `await release_ipam_pool_allocation(...)` for a
synchronous call.

Arguments mapping described in
[ReleaseIpamPoolAllocationRequestRequestTypeDef](./type_defs.md#releaseipampoolallocationrequestrequesttypedef).

Keyword-only arguments:

- `IpamPoolId`: `str` *(required)*
- `Cidr`: `str` *(required)*
- `DryRun`: `bool`
- `IpamPoolAllocationId`: `str`

Returns a `Coroutine` for
[ReleaseIpamPoolAllocationResultTypeDef](./type_defs.md#releaseipampoolallocationresulttypedef).

<a id="replace_iam_instance_profile_association"></a>

### replace_iam_instance_profile_association

Replaces an IAM instance profile for the specified running instance.

Type annotations for
`aiobotocore.create_client("ec2").replace_iam_instance_profile_association`
method.

Boto3 documentation:
[EC2.Client.replace_iam_instance_profile_association](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.replace_iam_instance_profile_association)

Asynchronous method. Use `await replace_iam_instance_profile_association(...)`
for a synchronous call.

Arguments mapping described in
[ReplaceIamInstanceProfileAssociationRequestRequestTypeDef](./type_defs.md#replaceiaminstanceprofileassociationrequestrequesttypedef).

Keyword-only arguments:

- `IamInstanceProfile`:
  [IamInstanceProfileSpecificationTypeDef](./type_defs.md#iaminstanceprofilespecificationtypedef)
  *(required)*
- `AssociationId`: `str` *(required)*

Returns a `Coroutine` for
[ReplaceIamInstanceProfileAssociationResultTypeDef](./type_defs.md#replaceiaminstanceprofileassociationresulttypedef).

<a id="replace_network_acl_association"></a>

### replace_network_acl_association

Changes which network ACL a subnet is associated with.

Type annotations for
`aiobotocore.create_client("ec2").replace_network_acl_association` method.

Boto3 documentation:
[EC2.Client.replace_network_acl_association](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.replace_network_acl_association)

Asynchronous method. Use `await replace_network_acl_association(...)` for a
synchronous call.

Arguments mapping described in
[ReplaceNetworkAclAssociationRequestRequestTypeDef](./type_defs.md#replacenetworkaclassociationrequestrequesttypedef).

Keyword-only arguments:

- `AssociationId`: `str` *(required)*
- `NetworkAclId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[ReplaceNetworkAclAssociationResultTypeDef](./type_defs.md#replacenetworkaclassociationresulttypedef).

<a id="replace_network_acl_entry"></a>

### replace_network_acl_entry

Replaces an entry (rule) in a network ACL.

Type annotations for
`aiobotocore.create_client("ec2").replace_network_acl_entry` method.

Boto3 documentation:
[EC2.Client.replace_network_acl_entry](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.replace_network_acl_entry)

Asynchronous method. Use `await replace_network_acl_entry(...)` for a
synchronous call.

Arguments mapping described in
[ReplaceNetworkAclEntryRequestRequestTypeDef](./type_defs.md#replacenetworkaclentryrequestrequesttypedef).

Keyword-only arguments:

- `Egress`: `bool` *(required)*
- `NetworkAclId`: `str` *(required)*
- `Protocol`: `str` *(required)*
- `RuleAction`: [RuleActionType](./literals.md#ruleactiontype) *(required)*
- `RuleNumber`: `int` *(required)*
- `CidrBlock`: `str`
- `DryRun`: `bool`
- `IcmpTypeCode`: [IcmpTypeCodeTypeDef](./type_defs.md#icmptypecodetypedef)
- `Ipv6CidrBlock`: `str`
- `PortRange`: [PortRangeTypeDef](./type_defs.md#portrangetypedef)

<a id="replace_route"></a>

### replace_route

Replaces an existing route within a route table in a VPC.

Type annotations for `aiobotocore.create_client("ec2").replace_route` method.

Boto3 documentation:
[EC2.Client.replace_route](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.replace_route)

Asynchronous method. Use `await replace_route(...)` for a synchronous call.

Arguments mapping described in
[ReplaceRouteRequestRequestTypeDef](./type_defs.md#replacerouterequestrequesttypedef).

Keyword-only arguments:

- `RouteTableId`: `str` *(required)*
- `DestinationCidrBlock`: `str`
- `DestinationIpv6CidrBlock`: `str`
- `DestinationPrefixListId`: `str`
- `DryRun`: `bool`
- `VpcEndpointId`: `str`
- `EgressOnlyInternetGatewayId`: `str`
- `GatewayId`: `str`
- `InstanceId`: `str`
- `LocalTarget`: `bool`
- `NatGatewayId`: `str`
- `TransitGatewayId`: `str`
- `LocalGatewayId`: `str`
- `CarrierGatewayId`: `str`
- `NetworkInterfaceId`: `str`
- `VpcPeeringConnectionId`: `str`
- `CoreNetworkArn`: `str`

<a id="replace_route_table_association"></a>

### replace_route_table_association

Changes the route table associated with a given subnet, internet gateway, or
virtual private gateway in a VPC.

Type annotations for
`aiobotocore.create_client("ec2").replace_route_table_association` method.

Boto3 documentation:
[EC2.Client.replace_route_table_association](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.replace_route_table_association)

Asynchronous method. Use `await replace_route_table_association(...)` for a
synchronous call.

Arguments mapping described in
[ReplaceRouteTableAssociationRequestRequestTypeDef](./type_defs.md#replaceroutetableassociationrequestrequesttypedef).

Keyword-only arguments:

- `AssociationId`: `str` *(required)*
- `RouteTableId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[ReplaceRouteTableAssociationResultTypeDef](./type_defs.md#replaceroutetableassociationresulttypedef).

<a id="replace_transit_gateway_route"></a>

### replace_transit_gateway_route

Replaces the specified route in the specified transit gateway route table.

Type annotations for
`aiobotocore.create_client("ec2").replace_transit_gateway_route` method.

Boto3 documentation:
[EC2.Client.replace_transit_gateway_route](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.replace_transit_gateway_route)

Asynchronous method. Use `await replace_transit_gateway_route(...)` for a
synchronous call.

Arguments mapping described in
[ReplaceTransitGatewayRouteRequestRequestTypeDef](./type_defs.md#replacetransitgatewayrouterequestrequesttypedef).

Keyword-only arguments:

- `DestinationCidrBlock`: `str` *(required)*
- `TransitGatewayRouteTableId`: `str` *(required)*
- `TransitGatewayAttachmentId`: `str`
- `Blackhole`: `bool`
- `DryRun`: `bool`

Returns a `Coroutine` for
[ReplaceTransitGatewayRouteResultTypeDef](./type_defs.md#replacetransitgatewayrouteresulttypedef).

<a id="report_instance_status"></a>

### report_instance_status

Submits feedback about the status of an instance.

Type annotations for `aiobotocore.create_client("ec2").report_instance_status`
method.

Boto3 documentation:
[EC2.Client.report_instance_status](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.report_instance_status)

Asynchronous method. Use `await report_instance_status(...)` for a synchronous
call.

Arguments mapping described in
[ReportInstanceStatusRequestRequestTypeDef](./type_defs.md#reportinstancestatusrequestrequesttypedef).

Keyword-only arguments:

- `Instances`: `Sequence`\[`str`\] *(required)*
- `ReasonCodes`:
  `Sequence`\[[ReportInstanceReasonCodesType](./literals.md#reportinstancereasoncodestype)\]
  *(required)*
- `Status`: [ReportStatusTypeType](./literals.md#reportstatustypetype)
  *(required)*
- `Description`: `str`
- `DryRun`: `bool`
- `EndTime`: `Union`\[`datetime`, `str`\]
- `StartTime`: `Union`\[`datetime`, `str`\]

<a id="request_spot_fleet"></a>

### request_spot_fleet

.

Type annotations for `aiobotocore.create_client("ec2").request_spot_fleet`
method.

Boto3 documentation:
[EC2.Client.request_spot_fleet](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.request_spot_fleet)

Asynchronous method. Use `await request_spot_fleet(...)` for a synchronous
call.

Arguments mapping described in
[RequestSpotFleetRequestRequestTypeDef](./type_defs.md#requestspotfleetrequestrequesttypedef).

Keyword-only arguments:

- `SpotFleetRequestConfig`:
  [SpotFleetRequestConfigDataTypeDef](./type_defs.md#spotfleetrequestconfigdatatypedef)
  *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[RequestSpotFleetResponseTypeDef](./type_defs.md#requestspotfleetresponsetypedef).

<a id="request_spot_instances"></a>

### request_spot_instances

Creates a Spot Instance request.

Type annotations for `aiobotocore.create_client("ec2").request_spot_instances`
method.

Boto3 documentation:
[EC2.Client.request_spot_instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.request_spot_instances)

Asynchronous method. Use `await request_spot_instances(...)` for a synchronous
call.

Arguments mapping described in
[RequestSpotInstancesRequestRequestTypeDef](./type_defs.md#requestspotinstancesrequestrequesttypedef).

Keyword-only arguments:

- `AvailabilityZoneGroup`: `str`
- `BlockDurationMinutes`: `int`
- `ClientToken`: `str`
- `DryRun`: `bool`
- `InstanceCount`: `int`
- `LaunchGroup`: `str`
- `LaunchSpecification`:
  [RequestSpotLaunchSpecificationTypeDef](./type_defs.md#requestspotlaunchspecificationtypedef)
- `SpotPrice`: `str`
- `Type`: [SpotInstanceTypeType](./literals.md#spotinstancetypetype)
- `ValidFrom`: `Union`\[`datetime`, `str`\]
- `ValidUntil`: `Union`\[`datetime`, `str`\]
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `InstanceInterruptionBehavior`:
  [InstanceInterruptionBehaviorType](./literals.md#instanceinterruptionbehaviortype)

Returns a `Coroutine` for
[RequestSpotInstancesResultTypeDef](./type_defs.md#requestspotinstancesresulttypedef).

<a id="reset_address_attribute"></a>

### reset_address_attribute

Resets the attribute of the specified IP address.

Type annotations for `aiobotocore.create_client("ec2").reset_address_attribute`
method.

Boto3 documentation:
[EC2.Client.reset_address_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.reset_address_attribute)

Asynchronous method. Use `await reset_address_attribute(...)` for a synchronous
call.

Arguments mapping described in
[ResetAddressAttributeRequestRequestTypeDef](./type_defs.md#resetaddressattributerequestrequesttypedef).

Keyword-only arguments:

- `AllocationId`: `str` *(required)*
- `Attribute`: `Literal['domain-name']` (see
  [AddressAttributeNameType](./literals.md#addressattributenametype))
  *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[ResetAddressAttributeResultTypeDef](./type_defs.md#resetaddressattributeresulttypedef).

<a id="reset_ebs_default_kms_key_id"></a>

### reset_ebs_default_kms_key_id

Resets the default KMS key for EBS encryption for your account in this Region
to the Amazon Web Services managed KMS key for EBS.

Type annotations for
`aiobotocore.create_client("ec2").reset_ebs_default_kms_key_id` method.

Boto3 documentation:
[EC2.Client.reset_ebs_default_kms_key_id](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.reset_ebs_default_kms_key_id)

Asynchronous method. Use `await reset_ebs_default_kms_key_id(...)` for a
synchronous call.

Arguments mapping described in
[ResetEbsDefaultKmsKeyIdRequestRequestTypeDef](./type_defs.md#resetebsdefaultkmskeyidrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`

Returns a `Coroutine` for
[ResetEbsDefaultKmsKeyIdResultTypeDef](./type_defs.md#resetebsdefaultkmskeyidresulttypedef).

<a id="reset_fpga_image_attribute"></a>

### reset_fpga_image_attribute

Resets the specified attribute of the specified Amazon FPGA Image (AFI) to its
default value.

Type annotations for
`aiobotocore.create_client("ec2").reset_fpga_image_attribute` method.

Boto3 documentation:
[EC2.Client.reset_fpga_image_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.reset_fpga_image_attribute)

Asynchronous method. Use `await reset_fpga_image_attribute(...)` for a
synchronous call.

Arguments mapping described in
[ResetFpgaImageAttributeRequestRequestTypeDef](./type_defs.md#resetfpgaimageattributerequestrequesttypedef).

Keyword-only arguments:

- `FpgaImageId`: `str` *(required)*
- `DryRun`: `bool`
- `Attribute`: `Literal['loadPermission']` (see
  [ResetFpgaImageAttributeNameType](./literals.md#resetfpgaimageattributenametype))

Returns a `Coroutine` for
[ResetFpgaImageAttributeResultTypeDef](./type_defs.md#resetfpgaimageattributeresulttypedef).

<a id="reset_image_attribute"></a>

### reset_image_attribute

Resets an attribute of an AMI to its default value.

Type annotations for `aiobotocore.create_client("ec2").reset_image_attribute`
method.

Boto3 documentation:
[EC2.Client.reset_image_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.reset_image_attribute)

Asynchronous method. Use `await reset_image_attribute(...)` for a synchronous
call.

Arguments mapping described in
[ResetImageAttributeRequestRequestTypeDef](./type_defs.md#resetimageattributerequestrequesttypedef).

Keyword-only arguments:

- `Attribute`: `Literal['launchPermission']` (see
  [ResetImageAttributeNameType](./literals.md#resetimageattributenametype))
  *(required)*
- `ImageId`: `str` *(required)*
- `DryRun`: `bool`

<a id="reset_instance_attribute"></a>

### reset_instance_attribute

Resets an attribute of an instance to its default value.

Type annotations for
`aiobotocore.create_client("ec2").reset_instance_attribute` method.

Boto3 documentation:
[EC2.Client.reset_instance_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.reset_instance_attribute)

Asynchronous method. Use `await reset_instance_attribute(...)` for a
synchronous call.

Arguments mapping described in
[ResetInstanceAttributeRequestRequestTypeDef](./type_defs.md#resetinstanceattributerequestrequesttypedef).

Keyword-only arguments:

- `Attribute`:
  [InstanceAttributeNameType](./literals.md#instanceattributenametype)
  *(required)*
- `InstanceId`: `str` *(required)*
- `DryRun`: `bool`

<a id="reset_network_interface_attribute"></a>

### reset_network_interface_attribute

Resets a network interface attribute.

Type annotations for
`aiobotocore.create_client("ec2").reset_network_interface_attribute` method.

Boto3 documentation:
[EC2.Client.reset_network_interface_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.reset_network_interface_attribute)

Asynchronous method. Use `await reset_network_interface_attribute(...)` for a
synchronous call.

Arguments mapping described in
[ResetNetworkInterfaceAttributeRequestRequestTypeDef](./type_defs.md#resetnetworkinterfaceattributerequestrequesttypedef).

Keyword-only arguments:

- `NetworkInterfaceId`: `str` *(required)*
- `DryRun`: `bool`
- `SourceDestCheck`: `str`

<a id="reset_snapshot_attribute"></a>

### reset_snapshot_attribute

Resets permission settings for the specified snapshot.

Type annotations for
`aiobotocore.create_client("ec2").reset_snapshot_attribute` method.

Boto3 documentation:
[EC2.Client.reset_snapshot_attribute](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.reset_snapshot_attribute)

Asynchronous method. Use `await reset_snapshot_attribute(...)` for a
synchronous call.

Arguments mapping described in
[ResetSnapshotAttributeRequestRequestTypeDef](./type_defs.md#resetsnapshotattributerequestrequesttypedef).

Keyword-only arguments:

- `Attribute`:
  [SnapshotAttributeNameType](./literals.md#snapshotattributenametype)
  *(required)*
- `SnapshotId`: `str` *(required)*
- `DryRun`: `bool`

<a id="restore_address_to_classic"></a>

### restore_address_to_classic

Restores an Elastic IP address that was previously moved to the EC2-VPC
platform back to the EC2-Classic platform.

Type annotations for
`aiobotocore.create_client("ec2").restore_address_to_classic` method.

Boto3 documentation:
[EC2.Client.restore_address_to_classic](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.restore_address_to_classic)

Asynchronous method. Use `await restore_address_to_classic(...)` for a
synchronous call.

Arguments mapping described in
[RestoreAddressToClassicRequestRequestTypeDef](./type_defs.md#restoreaddresstoclassicrequestrequesttypedef).

Keyword-only arguments:

- `PublicIp`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[RestoreAddressToClassicResultTypeDef](./type_defs.md#restoreaddresstoclassicresulttypedef).

<a id="restore_managed_prefix_list_version"></a>

### restore_managed_prefix_list_version

Restores the entries from a previous version of a managed prefix list to a new
version of the prefix list.

Type annotations for
`aiobotocore.create_client("ec2").restore_managed_prefix_list_version` method.

Boto3 documentation:
[EC2.Client.restore_managed_prefix_list_version](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.restore_managed_prefix_list_version)

Asynchronous method. Use `await restore_managed_prefix_list_version(...)` for a
synchronous call.

Arguments mapping described in
[RestoreManagedPrefixListVersionRequestRequestTypeDef](./type_defs.md#restoremanagedprefixlistversionrequestrequesttypedef).

Keyword-only arguments:

- `PrefixListId`: `str` *(required)*
- `PreviousVersion`: `int` *(required)*
- `CurrentVersion`: `int` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[RestoreManagedPrefixListVersionResultTypeDef](./type_defs.md#restoremanagedprefixlistversionresulttypedef).

<a id="restore_snapshot_from_recycle_bin"></a>

### restore_snapshot_from_recycle_bin

Restores a snapshot from the Recycle Bin.

Type annotations for
`aiobotocore.create_client("ec2").restore_snapshot_from_recycle_bin` method.

Boto3 documentation:
[EC2.Client.restore_snapshot_from_recycle_bin](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.restore_snapshot_from_recycle_bin)

Asynchronous method. Use `await restore_snapshot_from_recycle_bin(...)` for a
synchronous call.

Arguments mapping described in
[RestoreSnapshotFromRecycleBinRequestRequestTypeDef](./type_defs.md#restoresnapshotfromrecyclebinrequestrequesttypedef).

Keyword-only arguments:

- `SnapshotId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[RestoreSnapshotFromRecycleBinResultTypeDef](./type_defs.md#restoresnapshotfromrecyclebinresulttypedef).

<a id="restore_snapshot_tier"></a>

### restore_snapshot_tier

Restores an archived Amazon EBS snapshot for use temporarily or permanently, or
modifies the restore period or restore type for a snapshot that was previously
temporarily restored.

Type annotations for `aiobotocore.create_client("ec2").restore_snapshot_tier`
method.

Boto3 documentation:
[EC2.Client.restore_snapshot_tier](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.restore_snapshot_tier)

Asynchronous method. Use `await restore_snapshot_tier(...)` for a synchronous
call.

Arguments mapping described in
[RestoreSnapshotTierRequestRequestTypeDef](./type_defs.md#restoresnapshottierrequestrequesttypedef).

Keyword-only arguments:

- `SnapshotId`: `str` *(required)*
- `TemporaryRestoreDays`: `int`
- `PermanentRestore`: `bool`
- `DryRun`: `bool`

Returns a `Coroutine` for
[RestoreSnapshotTierResultTypeDef](./type_defs.md#restoresnapshottierresulttypedef).

<a id="revoke_client_vpn_ingress"></a>

### revoke_client_vpn_ingress

Removes an ingress authorization rule from a Client VPN endpoint.

Type annotations for
`aiobotocore.create_client("ec2").revoke_client_vpn_ingress` method.

Boto3 documentation:
[EC2.Client.revoke_client_vpn_ingress](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.revoke_client_vpn_ingress)

Asynchronous method. Use `await revoke_client_vpn_ingress(...)` for a
synchronous call.

Arguments mapping described in
[RevokeClientVpnIngressRequestRequestTypeDef](./type_defs.md#revokeclientvpningressrequestrequesttypedef).

Keyword-only arguments:

- `ClientVpnEndpointId`: `str` *(required)*
- `TargetNetworkCidr`: `str` *(required)*
- `AccessGroupId`: `str`
- `RevokeAllGroups`: `bool`
- `DryRun`: `bool`

Returns a `Coroutine` for
[RevokeClientVpnIngressResultTypeDef](./type_defs.md#revokeclientvpningressresulttypedef).

<a id="revoke_security_group_egress"></a>

### revoke_security_group_egress

Type annotations for
`aiobotocore.create_client("ec2").revoke_security_group_egress` method.

Boto3 documentation:
[EC2.Client.revoke_security_group_egress](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.revoke_security_group_egress)

Asynchronous method. Use `await revoke_security_group_egress(...)` for a
synchronous call.

Arguments mapping described in
[RevokeSecurityGroupEgressRequestRequestTypeDef](./type_defs.md#revokesecuritygroupegressrequestrequesttypedef).

Keyword-only arguments:

- `GroupId`: `str` *(required)*
- `DryRun`: `bool`
- `IpPermissions`:
  `Sequence`\[[IpPermissionTypeDef](./type_defs.md#ippermissiontypedef)\]
- `SecurityGroupRuleIds`: `Sequence`\[`str`\]
- `CidrIp`: `str`
- `FromPort`: `int`
- `IpProtocol`: `str`
- `ToPort`: `int`
- `SourceSecurityGroupName`: `str`
- `SourceSecurityGroupOwnerId`: `str`

Returns a `Coroutine` for
[RevokeSecurityGroupEgressResultTypeDef](./type_defs.md#revokesecuritygroupegressresulttypedef).

<a id="revoke_security_group_ingress"></a>

### revoke_security_group_ingress

Removes the specified inbound (ingress) rules from a security group.

Type annotations for
`aiobotocore.create_client("ec2").revoke_security_group_ingress` method.

Boto3 documentation:
[EC2.Client.revoke_security_group_ingress](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.revoke_security_group_ingress)

Asynchronous method. Use `await revoke_security_group_ingress(...)` for a
synchronous call.

Arguments mapping described in
[RevokeSecurityGroupIngressRequestRequestTypeDef](./type_defs.md#revokesecuritygroupingressrequestrequesttypedef).

Keyword-only arguments:

- `CidrIp`: `str`
- `FromPort`: `int`
- `GroupId`: `str`
- `GroupName`: `str`
- `IpPermissions`:
  `Sequence`\[[IpPermissionTypeDef](./type_defs.md#ippermissiontypedef)\]
- `IpProtocol`: `str`
- `SourceSecurityGroupName`: `str`
- `SourceSecurityGroupOwnerId`: `str`
- `ToPort`: `int`
- `DryRun`: `bool`
- `SecurityGroupRuleIds`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[RevokeSecurityGroupIngressResultTypeDef](./type_defs.md#revokesecuritygroupingressresulttypedef).

<a id="run_instances"></a>

### run_instances

Launches the specified number of instances using an AMI for which you have
permissions.

Type annotations for `aiobotocore.create_client("ec2").run_instances` method.

Boto3 documentation:
[EC2.Client.run_instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.run_instances)

Asynchronous method. Use `await run_instances(...)` for a synchronous call.

Arguments mapping described in
[RunInstancesRequestRequestTypeDef](./type_defs.md#runinstancesrequestrequesttypedef).

Keyword-only arguments:

- `MaxCount`: `int` *(required)*
- `MinCount`: `int` *(required)*
- `BlockDeviceMappings`:
  `Sequence`\[[BlockDeviceMappingTypeDef](./type_defs.md#blockdevicemappingtypedef)\]
- `ImageId`: `str`
- `InstanceType`: [InstanceTypeType](./literals.md#instancetypetype)
- `Ipv6AddressCount`: `int`
- `Ipv6Addresses`:
  `Sequence`\[[InstanceIpv6AddressTypeDef](./type_defs.md#instanceipv6addresstypedef)\]
- `KernelId`: `str`
- `KeyName`: `str`
- `Monitoring`:
  [RunInstancesMonitoringEnabledTypeDef](./type_defs.md#runinstancesmonitoringenabledtypedef)
- `Placement`: [PlacementTypeDef](./type_defs.md#placementtypedef)
- `RamdiskId`: `str`
- `SecurityGroupIds`: `Sequence`\[`str`\]
- `SecurityGroups`: `Sequence`\[`str`\]
- `SubnetId`: `str`
- `UserData`: `str`
- `AdditionalInfo`: `str`
- `ClientToken`: `str`
- `DisableApiTermination`: `bool`
- `DryRun`: `bool`
- `EbsOptimized`: `bool`
- `IamInstanceProfile`:
  [IamInstanceProfileSpecificationTypeDef](./type_defs.md#iaminstanceprofilespecificationtypedef)
- `InstanceInitiatedShutdownBehavior`:
  [ShutdownBehaviorType](./literals.md#shutdownbehaviortype)
- `NetworkInterfaces`:
  `Sequence`\[[InstanceNetworkInterfaceSpecificationTypeDef](./type_defs.md#instancenetworkinterfacespecificationtypedef)\]
- `PrivateIpAddress`: `str`
- `ElasticGpuSpecification`:
  `Sequence`\[[ElasticGpuSpecificationTypeDef](./type_defs.md#elasticgpuspecificationtypedef)\]
- `ElasticInferenceAccelerators`:
  `Sequence`\[[ElasticInferenceAcceleratorTypeDef](./type_defs.md#elasticinferenceacceleratortypedef)\]
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]
- `LaunchTemplate`:
  [LaunchTemplateSpecificationTypeDef](./type_defs.md#launchtemplatespecificationtypedef)
- `InstanceMarketOptions`:
  [InstanceMarketOptionsRequestTypeDef](./type_defs.md#instancemarketoptionsrequesttypedef)
- `CreditSpecification`:
  [CreditSpecificationRequestTypeDef](./type_defs.md#creditspecificationrequesttypedef)
- `CpuOptions`:
  [CpuOptionsRequestTypeDef](./type_defs.md#cpuoptionsrequesttypedef)
- `CapacityReservationSpecification`:
  [CapacityReservationSpecificationTypeDef](./type_defs.md#capacityreservationspecificationtypedef)
- `HibernationOptions`:
  [HibernationOptionsRequestTypeDef](./type_defs.md#hibernationoptionsrequesttypedef)
- `LicenseSpecifications`:
  `Sequence`\[[LicenseConfigurationRequestTypeDef](./type_defs.md#licenseconfigurationrequesttypedef)\]
- `MetadataOptions`:
  [InstanceMetadataOptionsRequestTypeDef](./type_defs.md#instancemetadataoptionsrequesttypedef)
- `EnclaveOptions`:
  [EnclaveOptionsRequestTypeDef](./type_defs.md#enclaveoptionsrequesttypedef)
- `PrivateDnsNameOptions`:
  [PrivateDnsNameOptionsRequestTypeDef](./type_defs.md#privatednsnameoptionsrequesttypedef)

Returns a `Coroutine` for
[ReservationResponseMetadataTypeDef](./type_defs.md#reservationresponsemetadatatypedef).

<a id="run_scheduled_instances"></a>

### run_scheduled_instances

Launches the specified Scheduled Instances.

Type annotations for `aiobotocore.create_client("ec2").run_scheduled_instances`
method.

Boto3 documentation:
[EC2.Client.run_scheduled_instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.run_scheduled_instances)

Asynchronous method. Use `await run_scheduled_instances(...)` for a synchronous
call.

Arguments mapping described in
[RunScheduledInstancesRequestRequestTypeDef](./type_defs.md#runscheduledinstancesrequestrequesttypedef).

Keyword-only arguments:

- `LaunchSpecification`:
  [ScheduledInstancesLaunchSpecificationTypeDef](./type_defs.md#scheduledinstanceslaunchspecificationtypedef)
  *(required)*
- `ScheduledInstanceId`: `str` *(required)*
- `ClientToken`: `str`
- `DryRun`: `bool`
- `InstanceCount`: `int`

Returns a `Coroutine` for
[RunScheduledInstancesResultTypeDef](./type_defs.md#runscheduledinstancesresulttypedef).

<a id="search_local_gateway_routes"></a>

### search_local_gateway_routes

Searches for routes in the specified local gateway route table.

Type annotations for
`aiobotocore.create_client("ec2").search_local_gateway_routes` method.

Boto3 documentation:
[EC2.Client.search_local_gateway_routes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.search_local_gateway_routes)

Asynchronous method. Use `await search_local_gateway_routes(...)` for a
synchronous call.

Arguments mapping described in
[SearchLocalGatewayRoutesRequestRequestTypeDef](./type_defs.md#searchlocalgatewayroutesrequestrequesttypedef).

Keyword-only arguments:

- `LocalGatewayRouteTableId`: `str` *(required)*
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[SearchLocalGatewayRoutesResultTypeDef](./type_defs.md#searchlocalgatewayroutesresulttypedef).

<a id="search_transit_gateway_multicast_groups"></a>

### search_transit_gateway_multicast_groups

Searches one or more transit gateway multicast groups and returns the group
membership information.

Type annotations for
`aiobotocore.create_client("ec2").search_transit_gateway_multicast_groups`
method.

Boto3 documentation:
[EC2.Client.search_transit_gateway_multicast_groups](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.search_transit_gateway_multicast_groups)

Asynchronous method. Use `await search_transit_gateway_multicast_groups(...)`
for a synchronous call.

Arguments mapping described in
[SearchTransitGatewayMulticastGroupsRequestRequestTypeDef](./type_defs.md#searchtransitgatewaymulticastgroupsrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayMulticastDomainId`: `str`
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
- `MaxResults`: `int`
- `NextToken`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[SearchTransitGatewayMulticastGroupsResultTypeDef](./type_defs.md#searchtransitgatewaymulticastgroupsresulttypedef).

<a id="search_transit_gateway_routes"></a>

### search_transit_gateway_routes

Searches for routes in the specified transit gateway route table.

Type annotations for
`aiobotocore.create_client("ec2").search_transit_gateway_routes` method.

Boto3 documentation:
[EC2.Client.search_transit_gateway_routes](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.search_transit_gateway_routes)

Asynchronous method. Use `await search_transit_gateway_routes(...)` for a
synchronous call.

Arguments mapping described in
[SearchTransitGatewayRoutesRequestRequestTypeDef](./type_defs.md#searchtransitgatewayroutesrequestrequesttypedef).

Keyword-only arguments:

- `TransitGatewayRouteTableId`: `str` *(required)*
- `Filters`: `Sequence`\[[FilterTypeDef](./type_defs.md#filtertypedef)\]
  *(required)*
- `MaxResults`: `int`
- `DryRun`: `bool`

Returns a `Coroutine` for
[SearchTransitGatewayRoutesResultTypeDef](./type_defs.md#searchtransitgatewayroutesresulttypedef).

<a id="send_diagnostic_interrupt"></a>

### send_diagnostic_interrupt

Sends a diagnostic interrupt to the specified Amazon EC2 instance to trigger a
*kernel panic* (on Linux instances), or a *blue screen* /*stop error* (on
Windows instances).

Type annotations for
`aiobotocore.create_client("ec2").send_diagnostic_interrupt` method.

Boto3 documentation:
[EC2.Client.send_diagnostic_interrupt](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.send_diagnostic_interrupt)

Asynchronous method. Use `await send_diagnostic_interrupt(...)` for a
synchronous call.

Arguments mapping described in
[SendDiagnosticInterruptRequestRequestTypeDef](./type_defs.md#senddiagnosticinterruptrequestrequesttypedef).

Keyword-only arguments:

- `InstanceId`: `str` *(required)*
- `DryRun`: `bool`

<a id="start_instances"></a>

### start_instances

Starts an Amazon EBS-backed instance that you've previously stopped.

Type annotations for `aiobotocore.create_client("ec2").start_instances` method.

Boto3 documentation:
[EC2.Client.start_instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.start_instances)

Asynchronous method. Use `await start_instances(...)` for a synchronous call.

Arguments mapping described in
[StartInstancesRequestRequestTypeDef](./type_defs.md#startinstancesrequestrequesttypedef).

Keyword-only arguments:

- `InstanceIds`: `Sequence`\[`str`\] *(required)*
- `AdditionalInfo`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[StartInstancesResultTypeDef](./type_defs.md#startinstancesresulttypedef).

<a id="start_network_insights_access_scope_analysis"></a>

### start_network_insights_access_scope_analysis

Starts analyzing the specified Network Access Scope.

Type annotations for
`aiobotocore.create_client("ec2").start_network_insights_access_scope_analysis`
method.

Boto3 documentation:
[EC2.Client.start_network_insights_access_scope_analysis](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.start_network_insights_access_scope_analysis)

Asynchronous method. Use
`await start_network_insights_access_scope_analysis(...)` for a synchronous
call.

Arguments mapping described in
[StartNetworkInsightsAccessScopeAnalysisRequestRequestTypeDef](./type_defs.md#startnetworkinsightsaccessscopeanalysisrequestrequesttypedef).

Keyword-only arguments:

- `NetworkInsightsAccessScopeId`: `str` *(required)*
- `ClientToken`: `str` *(required)*
- `DryRun`: `bool`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for
[StartNetworkInsightsAccessScopeAnalysisResultTypeDef](./type_defs.md#startnetworkinsightsaccessscopeanalysisresulttypedef).

<a id="start_network_insights_analysis"></a>

### start_network_insights_analysis

Starts analyzing the specified path.

Type annotations for
`aiobotocore.create_client("ec2").start_network_insights_analysis` method.

Boto3 documentation:
[EC2.Client.start_network_insights_analysis](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.start_network_insights_analysis)

Asynchronous method. Use `await start_network_insights_analysis(...)` for a
synchronous call.

Arguments mapping described in
[StartNetworkInsightsAnalysisRequestRequestTypeDef](./type_defs.md#startnetworkinsightsanalysisrequestrequesttypedef).

Keyword-only arguments:

- `NetworkInsightsPathId`: `str` *(required)*
- `ClientToken`: `str` *(required)*
- `FilterInArns`: `Sequence`\[`str`\]
- `DryRun`: `bool`
- `TagSpecifications`:
  `Sequence`\[[TagSpecificationTypeDef](./type_defs.md#tagspecificationtypedef)\]

Returns a `Coroutine` for
[StartNetworkInsightsAnalysisResultTypeDef](./type_defs.md#startnetworkinsightsanalysisresulttypedef).

<a id="start_vpc_endpoint_service_private_dns_verification"></a>

### start_vpc_endpoint_service_private_dns_verification

Initiates the verification process to prove that the service provider owns the
private DNS name domain for the endpoint service.

Type annotations for
`aiobotocore.create_client("ec2").start_vpc_endpoint_service_private_dns_verification`
method.

Boto3 documentation:
[EC2.Client.start_vpc_endpoint_service_private_dns_verification](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.start_vpc_endpoint_service_private_dns_verification)

Asynchronous method. Use
`await start_vpc_endpoint_service_private_dns_verification(...)` for a
synchronous call.

Arguments mapping described in
[StartVpcEndpointServicePrivateDnsVerificationRequestRequestTypeDef](./type_defs.md#startvpcendpointserviceprivatednsverificationrequestrequesttypedef).

Keyword-only arguments:

- `ServiceId`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[StartVpcEndpointServicePrivateDnsVerificationResultTypeDef](./type_defs.md#startvpcendpointserviceprivatednsverificationresulttypedef).

<a id="stop_instances"></a>

### stop_instances

Stops an Amazon EBS-backed instance.

Type annotations for `aiobotocore.create_client("ec2").stop_instances` method.

Boto3 documentation:
[EC2.Client.stop_instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.stop_instances)

Asynchronous method. Use `await stop_instances(...)` for a synchronous call.

Arguments mapping described in
[StopInstancesRequestRequestTypeDef](./type_defs.md#stopinstancesrequestrequesttypedef).

Keyword-only arguments:

- `InstanceIds`: `Sequence`\[`str`\] *(required)*
- `Hibernate`: `bool`
- `DryRun`: `bool`
- `Force`: `bool`

Returns a `Coroutine` for
[StopInstancesResultTypeDef](./type_defs.md#stopinstancesresulttypedef).

<a id="terminate_client_vpn_connections"></a>

### terminate_client_vpn_connections

Terminates active Client VPN endpoint connections.

Type annotations for
`aiobotocore.create_client("ec2").terminate_client_vpn_connections` method.

Boto3 documentation:
[EC2.Client.terminate_client_vpn_connections](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.terminate_client_vpn_connections)

Asynchronous method. Use `await terminate_client_vpn_connections(...)` for a
synchronous call.

Arguments mapping described in
[TerminateClientVpnConnectionsRequestRequestTypeDef](./type_defs.md#terminateclientvpnconnectionsrequestrequesttypedef).

Keyword-only arguments:

- `ClientVpnEndpointId`: `str` *(required)*
- `ConnectionId`: `str`
- `Username`: `str`
- `DryRun`: `bool`

Returns a `Coroutine` for
[TerminateClientVpnConnectionsResultTypeDef](./type_defs.md#terminateclientvpnconnectionsresulttypedef).

<a id="terminate_instances"></a>

### terminate_instances

Shuts down the specified instances.

Type annotations for `aiobotocore.create_client("ec2").terminate_instances`
method.

Boto3 documentation:
[EC2.Client.terminate_instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.terminate_instances)

Asynchronous method. Use `await terminate_instances(...)` for a synchronous
call.

Arguments mapping described in
[TerminateInstancesRequestRequestTypeDef](./type_defs.md#terminateinstancesrequestrequesttypedef).

Keyword-only arguments:

- `InstanceIds`: `Sequence`\[`str`\] *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[TerminateInstancesResultTypeDef](./type_defs.md#terminateinstancesresulttypedef).

<a id="unassign_ipv6_addresses"></a>

### unassign_ipv6_addresses

Unassigns one or more IPv6 addresses IPv4 Prefix Delegation prefixes from a
network interface.

Type annotations for `aiobotocore.create_client("ec2").unassign_ipv6_addresses`
method.

Boto3 documentation:
[EC2.Client.unassign_ipv6_addresses](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.unassign_ipv6_addresses)

Asynchronous method. Use `await unassign_ipv6_addresses(...)` for a synchronous
call.

Arguments mapping described in
[UnassignIpv6AddressesRequestRequestTypeDef](./type_defs.md#unassignipv6addressesrequestrequesttypedef).

Keyword-only arguments:

- `NetworkInterfaceId`: `str` *(required)*
- `Ipv6Addresses`: `Sequence`\[`str`\]
- `Ipv6Prefixes`: `Sequence`\[`str`\]

Returns a `Coroutine` for
[UnassignIpv6AddressesResultTypeDef](./type_defs.md#unassignipv6addressesresulttypedef).

<a id="unassign_private_ip_addresses"></a>

### unassign_private_ip_addresses

Unassigns one or more secondary private IP addresses, or IPv4 Prefix Delegation
prefixes from a network interface.

Type annotations for
`aiobotocore.create_client("ec2").unassign_private_ip_addresses` method.

Boto3 documentation:
[EC2.Client.unassign_private_ip_addresses](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.unassign_private_ip_addresses)

Asynchronous method. Use `await unassign_private_ip_addresses(...)` for a
synchronous call.

Arguments mapping described in
[UnassignPrivateIpAddressesRequestRequestTypeDef](./type_defs.md#unassignprivateipaddressesrequestrequesttypedef).

Keyword-only arguments:

- `NetworkInterfaceId`: `str` *(required)*
- `PrivateIpAddresses`: `Sequence`\[`str`\]
- `Ipv4Prefixes`: `Sequence`\[`str`\]

<a id="unmonitor_instances"></a>

### unmonitor_instances

Disables detailed monitoring for a running instance.

Type annotations for `aiobotocore.create_client("ec2").unmonitor_instances`
method.

Boto3 documentation:
[EC2.Client.unmonitor_instances](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.unmonitor_instances)

Asynchronous method. Use `await unmonitor_instances(...)` for a synchronous
call.

Arguments mapping described in
[UnmonitorInstancesRequestRequestTypeDef](./type_defs.md#unmonitorinstancesrequestrequesttypedef).

Keyword-only arguments:

- `InstanceIds`: `Sequence`\[`str`\] *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[UnmonitorInstancesResultTypeDef](./type_defs.md#unmonitorinstancesresulttypedef).

<a id="update_security_group_rule_descriptions_egress"></a>

### update_security_group_rule_descriptions_egress

Type annotations for
`aiobotocore.create_client("ec2").update_security_group_rule_descriptions_egress`
method.

Boto3 documentation:
[EC2.Client.update_security_group_rule_descriptions_egress](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.update_security_group_rule_descriptions_egress)

Asynchronous method. Use
`await update_security_group_rule_descriptions_egress(...)` for a synchronous
call.

Arguments mapping described in
[UpdateSecurityGroupRuleDescriptionsEgressRequestRequestTypeDef](./type_defs.md#updatesecuritygroupruledescriptionsegressrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `GroupId`: `str`
- `GroupName`: `str`
- `IpPermissions`:
  `Sequence`\[[IpPermissionTypeDef](./type_defs.md#ippermissiontypedef)\]
- `SecurityGroupRuleDescriptions`:
  `Sequence`\[[SecurityGroupRuleDescriptionTypeDef](./type_defs.md#securitygroupruledescriptiontypedef)\]

Returns a `Coroutine` for
[UpdateSecurityGroupRuleDescriptionsEgressResultTypeDef](./type_defs.md#updatesecuritygroupruledescriptionsegressresulttypedef).

<a id="update_security_group_rule_descriptions_ingress"></a>

### update_security_group_rule_descriptions_ingress

Updates the description of an ingress (inbound) security group rule.

Type annotations for
`aiobotocore.create_client("ec2").update_security_group_rule_descriptions_ingress`
method.

Boto3 documentation:
[EC2.Client.update_security_group_rule_descriptions_ingress](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.update_security_group_rule_descriptions_ingress)

Asynchronous method. Use
`await update_security_group_rule_descriptions_ingress(...)` for a synchronous
call.

Arguments mapping described in
[UpdateSecurityGroupRuleDescriptionsIngressRequestRequestTypeDef](./type_defs.md#updatesecuritygroupruledescriptionsingressrequestrequesttypedef).

Keyword-only arguments:

- `DryRun`: `bool`
- `GroupId`: `str`
- `GroupName`: `str`
- `IpPermissions`:
  `Sequence`\[[IpPermissionTypeDef](./type_defs.md#ippermissiontypedef)\]
- `SecurityGroupRuleDescriptions`:
  `Sequence`\[[SecurityGroupRuleDescriptionTypeDef](./type_defs.md#securitygroupruledescriptiontypedef)\]

Returns a `Coroutine` for
[UpdateSecurityGroupRuleDescriptionsIngressResultTypeDef](./type_defs.md#updatesecuritygroupruledescriptionsingressresulttypedef).

<a id="withdraw_byoip_cidr"></a>

### withdraw_byoip_cidr

Stops advertising an address range that is provisioned as an address pool.

Type annotations for `aiobotocore.create_client("ec2").withdraw_byoip_cidr`
method.

Boto3 documentation:
[EC2.Client.withdraw_byoip_cidr](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ec2.html#EC2.Client.withdraw_byoip_cidr)

Asynchronous method. Use `await withdraw_byoip_cidr(...)` for a synchronous
call.

Arguments mapping described in
[WithdrawByoipCidrRequestRequestTypeDef](./type_defs.md#withdrawbyoipcidrrequestrequesttypedef).

Keyword-only arguments:

- `Cidr`: `str` *(required)*
- `DryRun`: `bool`

Returns a `Coroutine` for
[WithdrawByoipCidrResultTypeDef](./type_defs.md#withdrawbyoipcidrresulttypedef).

<a id="get_paginator"></a>

### get_paginator

Type annotations for `aiobotocore.create_client("ec2").get_paginator` method
with overloads.

- `client.get_paginator("describe_addresses_attribute")` ->
  [DescribeAddressesAttributePaginator](./paginators.md#describeaddressesattributepaginator)
- `client.get_paginator("describe_byoip_cidrs")` ->
  [DescribeByoipCidrsPaginator](./paginators.md#describebyoipcidrspaginator)
- `client.get_paginator("describe_capacity_reservation_fleets")` ->
  [DescribeCapacityReservationFleetsPaginator](./paginators.md#describecapacityreservationfleetspaginator)
- `client.get_paginator("describe_capacity_reservations")` ->
  [DescribeCapacityReservationsPaginator](./paginators.md#describecapacityreservationspaginator)
- `client.get_paginator("describe_carrier_gateways")` ->
  [DescribeCarrierGatewaysPaginator](./paginators.md#describecarriergatewayspaginator)
- `client.get_paginator("describe_classic_link_instances")` ->
  [DescribeClassicLinkInstancesPaginator](./paginators.md#describeclassiclinkinstancespaginator)
- `client.get_paginator("describe_client_vpn_authorization_rules")` ->
  [DescribeClientVpnAuthorizationRulesPaginator](./paginators.md#describeclientvpnauthorizationrulespaginator)
- `client.get_paginator("describe_client_vpn_connections")` ->
  [DescribeClientVpnConnectionsPaginator](./paginators.md#describeclientvpnconnectionspaginator)
- `client.get_paginator("describe_client_vpn_endpoints")` ->
  [DescribeClientVpnEndpointsPaginator](./paginators.md#describeclientvpnendpointspaginator)
- `client.get_paginator("describe_client_vpn_routes")` ->
  [DescribeClientVpnRoutesPaginator](./paginators.md#describeclientvpnroutespaginator)
- `client.get_paginator("describe_client_vpn_target_networks")` ->
  [DescribeClientVpnTargetNetworksPaginator](./paginators.md#describeclientvpntargetnetworkspaginator)
- `client.get_paginator("describe_coip_pools")` ->
  [DescribeCoipPoolsPaginator](./paginators.md#describecoippoolspaginator)
- `client.get_paginator("describe_dhcp_options")` ->
  [DescribeDhcpOptionsPaginator](./paginators.md#describedhcpoptionspaginator)
- `client.get_paginator("describe_egress_only_internet_gateways")` ->
  [DescribeEgressOnlyInternetGatewaysPaginator](./paginators.md#describeegressonlyinternetgatewayspaginator)
- `client.get_paginator("describe_export_image_tasks")` ->
  [DescribeExportImageTasksPaginator](./paginators.md#describeexportimagetaskspaginator)
- `client.get_paginator("describe_fast_snapshot_restores")` ->
  [DescribeFastSnapshotRestoresPaginator](./paginators.md#describefastsnapshotrestorespaginator)
- `client.get_paginator("describe_fleets")` ->
  [DescribeFleetsPaginator](./paginators.md#describefleetspaginator)
- `client.get_paginator("describe_flow_logs")` ->
  [DescribeFlowLogsPaginator](./paginators.md#describeflowlogspaginator)
- `client.get_paginator("describe_fpga_images")` ->
  [DescribeFpgaImagesPaginator](./paginators.md#describefpgaimagespaginator)
- `client.get_paginator("describe_host_reservation_offerings")` ->
  [DescribeHostReservationOfferingsPaginator](./paginators.md#describehostreservationofferingspaginator)
- `client.get_paginator("describe_host_reservations")` ->
  [DescribeHostReservationsPaginator](./paginators.md#describehostreservationspaginator)
- `client.get_paginator("describe_hosts")` ->
  [DescribeHostsPaginator](./paginators.md#describehostspaginator)
- `client.get_paginator("describe_iam_instance_profile_associations")` ->
  [DescribeIamInstanceProfileAssociationsPaginator](./paginators.md#describeiaminstanceprofileassociationspaginator)
- `client.get_paginator("describe_import_image_tasks")` ->
  [DescribeImportImageTasksPaginator](./paginators.md#describeimportimagetaskspaginator)
- `client.get_paginator("describe_import_snapshot_tasks")` ->
  [DescribeImportSnapshotTasksPaginator](./paginators.md#describeimportsnapshottaskspaginator)
- `client.get_paginator("describe_instance_credit_specifications")` ->
  [DescribeInstanceCreditSpecificationsPaginator](./paginators.md#describeinstancecreditspecificationspaginator)
- `client.get_paginator("describe_instance_event_windows")` ->
  [DescribeInstanceEventWindowsPaginator](./paginators.md#describeinstanceeventwindowspaginator)
- `client.get_paginator("describe_instance_status")` ->
  [DescribeInstanceStatusPaginator](./paginators.md#describeinstancestatuspaginator)
- `client.get_paginator("describe_instance_type_offerings")` ->
  [DescribeInstanceTypeOfferingsPaginator](./paginators.md#describeinstancetypeofferingspaginator)
- `client.get_paginator("describe_instance_types")` ->
  [DescribeInstanceTypesPaginator](./paginators.md#describeinstancetypespaginator)
- `client.get_paginator("describe_instances")` ->
  [DescribeInstancesPaginator](./paginators.md#describeinstancespaginator)
- `client.get_paginator("describe_internet_gateways")` ->
  [DescribeInternetGatewaysPaginator](./paginators.md#describeinternetgatewayspaginator)
- `client.get_paginator("describe_ipam_pools")` ->
  [DescribeIpamPoolsPaginator](./paginators.md#describeipampoolspaginator)
- `client.get_paginator("describe_ipam_scopes")` ->
  [DescribeIpamScopesPaginator](./paginators.md#describeipamscopespaginator)
- `client.get_paginator("describe_ipams")` ->
  [DescribeIpamsPaginator](./paginators.md#describeipamspaginator)
- `client.get_paginator("describe_ipv6_pools")` ->
  [DescribeIpv6PoolsPaginator](./paginators.md#describeipv6poolspaginator)
- `client.get_paginator("describe_launch_template_versions")` ->
  [DescribeLaunchTemplateVersionsPaginator](./paginators.md#describelaunchtemplateversionspaginator)
- `client.get_paginator("describe_launch_templates")` ->
  [DescribeLaunchTemplatesPaginator](./paginators.md#describelaunchtemplatespaginator)
- `client.get_paginator("describe_local_gateway_route_table_virtual_interface_group_associations")`
  ->
  [DescribeLocalGatewayRouteTableVirtualInterfaceGroupAssociationsPaginator](./paginators.md#describelocalgatewayroutetablevirtualinterfacegroupassociationspaginator)
- `client.get_paginator("describe_local_gateway_route_table_vpc_associations")`
  ->
  [DescribeLocalGatewayRouteTableVpcAssociationsPaginator](./paginators.md#describelocalgatewayroutetablevpcassociationspaginator)
- `client.get_paginator("describe_local_gateway_route_tables")` ->
  [DescribeLocalGatewayRouteTablesPaginator](./paginators.md#describelocalgatewayroutetablespaginator)
- `client.get_paginator("describe_local_gateway_virtual_interface_groups")` ->
  [DescribeLocalGatewayVirtualInterfaceGroupsPaginator](./paginators.md#describelocalgatewayvirtualinterfacegroupspaginator)
- `client.get_paginator("describe_local_gateway_virtual_interfaces")` ->
  [DescribeLocalGatewayVirtualInterfacesPaginator](./paginators.md#describelocalgatewayvirtualinterfacespaginator)
- `client.get_paginator("describe_local_gateways")` ->
  [DescribeLocalGatewaysPaginator](./paginators.md#describelocalgatewayspaginator)
- `client.get_paginator("describe_managed_prefix_lists")` ->
  [DescribeManagedPrefixListsPaginator](./paginators.md#describemanagedprefixlistspaginator)
- `client.get_paginator("describe_moving_addresses")` ->
  [DescribeMovingAddressesPaginator](./paginators.md#describemovingaddressespaginator)
- `client.get_paginator("describe_nat_gateways")` ->
  [DescribeNatGatewaysPaginator](./paginators.md#describenatgatewayspaginator)
- `client.get_paginator("describe_network_acls")` ->
  [DescribeNetworkAclsPaginator](./paginators.md#describenetworkaclspaginator)
- `client.get_paginator("describe_network_insights_access_scope_analyses")` ->
  [DescribeNetworkInsightsAccessScopeAnalysesPaginator](./paginators.md#describenetworkinsightsaccessscopeanalysespaginator)
- `client.get_paginator("describe_network_insights_access_scopes")` ->
  [DescribeNetworkInsightsAccessScopesPaginator](./paginators.md#describenetworkinsightsaccessscopespaginator)
- `client.get_paginator("describe_network_insights_analyses")` ->
  [DescribeNetworkInsightsAnalysesPaginator](./paginators.md#describenetworkinsightsanalysespaginator)
- `client.get_paginator("describe_network_insights_paths")` ->
  [DescribeNetworkInsightsPathsPaginator](./paginators.md#describenetworkinsightspathspaginator)
- `client.get_paginator("describe_network_interface_permissions")` ->
  [DescribeNetworkInterfacePermissionsPaginator](./paginators.md#describenetworkinterfacepermissionspaginator)
- `client.get_paginator("describe_network_interfaces")` ->
  [DescribeNetworkInterfacesPaginator](./paginators.md#describenetworkinterfacespaginator)
- `client.get_paginator("describe_prefix_lists")` ->
  [DescribePrefixListsPaginator](./paginators.md#describeprefixlistspaginator)
- `client.get_paginator("describe_principal_id_format")` ->
  [DescribePrincipalIdFormatPaginator](./paginators.md#describeprincipalidformatpaginator)
- `client.get_paginator("describe_public_ipv4_pools")` ->
  [DescribePublicIpv4PoolsPaginator](./paginators.md#describepublicipv4poolspaginator)
- `client.get_paginator("describe_replace_root_volume_tasks")` ->
  [DescribeReplaceRootVolumeTasksPaginator](./paginators.md#describereplacerootvolumetaskspaginator)
- `client.get_paginator("describe_reserved_instances_modifications")` ->
  [DescribeReservedInstancesModificationsPaginator](./paginators.md#describereservedinstancesmodificationspaginator)
- `client.get_paginator("describe_reserved_instances_offerings")` ->
  [DescribeReservedInstancesOfferingsPaginator](./paginators.md#describereservedinstancesofferingspaginator)
- `client.get_paginator("describe_route_tables")` ->
  [DescribeRouteTablesPaginator](./paginators.md#describeroutetablespaginator)
- `client.get_paginator("describe_scheduled_instance_availability")` ->
  [DescribeScheduledInstanceAvailabilityPaginator](./paginators.md#describescheduledinstanceavailabilitypaginator)
- `client.get_paginator("describe_scheduled_instances")` ->
  [DescribeScheduledInstancesPaginator](./paginators.md#describescheduledinstancespaginator)
- `client.get_paginator("describe_security_group_rules")` ->
  [DescribeSecurityGroupRulesPaginator](./paginators.md#describesecuritygrouprulespaginator)
- `client.get_paginator("describe_security_groups")` ->
  [DescribeSecurityGroupsPaginator](./paginators.md#describesecuritygroupspaginator)
- `client.get_paginator("describe_snapshot_tier_status")` ->
  [DescribeSnapshotTierStatusPaginator](./paginators.md#describesnapshottierstatuspaginator)
- `client.get_paginator("describe_snapshots")` ->
  [DescribeSnapshotsPaginator](./paginators.md#describesnapshotspaginator)
- `client.get_paginator("describe_spot_fleet_instances")` ->
  [DescribeSpotFleetInstancesPaginator](./paginators.md#describespotfleetinstancespaginator)
- `client.get_paginator("describe_spot_fleet_requests")` ->
  [DescribeSpotFleetRequestsPaginator](./paginators.md#describespotfleetrequestspaginator)
- `client.get_paginator("describe_spot_instance_requests")` ->
  [DescribeSpotInstanceRequestsPaginator](./paginators.md#describespotinstancerequestspaginator)
- `client.get_paginator("describe_spot_price_history")` ->
  [DescribeSpotPriceHistoryPaginator](./paginators.md#describespotpricehistorypaginator)
- `client.get_paginator("describe_stale_security_groups")` ->
  [DescribeStaleSecurityGroupsPaginator](./paginators.md#describestalesecuritygroupspaginator)
- `client.get_paginator("describe_store_image_tasks")` ->
  [DescribeStoreImageTasksPaginator](./paginators.md#describestoreimagetaskspaginator)
- `client.get_paginator("describe_subnets")` ->
  [DescribeSubnetsPaginator](./paginators.md#describesubnetspaginator)
- `client.get_paginator("describe_tags")` ->
  [DescribeTagsPaginator](./paginators.md#describetagspaginator)
- `client.get_paginator("describe_traffic_mirror_filters")` ->
  [DescribeTrafficMirrorFiltersPaginator](./paginators.md#describetrafficmirrorfilterspaginator)
- `client.get_paginator("describe_traffic_mirror_sessions")` ->
  [DescribeTrafficMirrorSessionsPaginator](./paginators.md#describetrafficmirrorsessionspaginator)
- `client.get_paginator("describe_traffic_mirror_targets")` ->
  [DescribeTrafficMirrorTargetsPaginator](./paginators.md#describetrafficmirrortargetspaginator)
- `client.get_paginator("describe_transit_gateway_attachments")` ->
  [DescribeTransitGatewayAttachmentsPaginator](./paginators.md#describetransitgatewayattachmentspaginator)
- `client.get_paginator("describe_transit_gateway_connect_peers")` ->
  [DescribeTransitGatewayConnectPeersPaginator](./paginators.md#describetransitgatewayconnectpeerspaginator)
- `client.get_paginator("describe_transit_gateway_connects")` ->
  [DescribeTransitGatewayConnectsPaginator](./paginators.md#describetransitgatewayconnectspaginator)
- `client.get_paginator("describe_transit_gateway_multicast_domains")` ->
  [DescribeTransitGatewayMulticastDomainsPaginator](./paginators.md#describetransitgatewaymulticastdomainspaginator)
- `client.get_paginator("describe_transit_gateway_peering_attachments")` ->
  [DescribeTransitGatewayPeeringAttachmentsPaginator](./paginators.md#describetransitgatewaypeeringattachmentspaginator)
- `client.get_paginator("describe_transit_gateway_route_tables")` ->
  [DescribeTransitGatewayRouteTablesPaginator](./paginators.md#describetransitgatewayroutetablespaginator)
- `client.get_paginator("describe_transit_gateway_vpc_attachments")` ->
  [DescribeTransitGatewayVpcAttachmentsPaginator](./paginators.md#describetransitgatewayvpcattachmentspaginator)
- `client.get_paginator("describe_transit_gateways")` ->
  [DescribeTransitGatewaysPaginator](./paginators.md#describetransitgatewayspaginator)
- `client.get_paginator("describe_trunk_interface_associations")` ->
  [DescribeTrunkInterfaceAssociationsPaginator](./paginators.md#describetrunkinterfaceassociationspaginator)
- `client.get_paginator("describe_volume_status")` ->
  [DescribeVolumeStatusPaginator](./paginators.md#describevolumestatuspaginator)
- `client.get_paginator("describe_volumes")` ->
  [DescribeVolumesPaginator](./paginators.md#describevolumespaginator)
- `client.get_paginator("describe_volumes_modifications")` ->
  [DescribeVolumesModificationsPaginator](./paginators.md#describevolumesmodificationspaginator)
- `client.get_paginator("describe_vpc_classic_link_dns_support")` ->
  [DescribeVpcClassicLinkDnsSupportPaginator](./paginators.md#describevpcclassiclinkdnssupportpaginator)
- `client.get_paginator("describe_vpc_endpoint_connection_notifications")` ->
  [DescribeVpcEndpointConnectionNotificationsPaginator](./paginators.md#describevpcendpointconnectionnotificationspaginator)
- `client.get_paginator("describe_vpc_endpoint_connections")` ->
  [DescribeVpcEndpointConnectionsPaginator](./paginators.md#describevpcendpointconnectionspaginator)
- `client.get_paginator("describe_vpc_endpoint_service_configurations")` ->
  [DescribeVpcEndpointServiceConfigurationsPaginator](./paginators.md#describevpcendpointserviceconfigurationspaginator)
- `client.get_paginator("describe_vpc_endpoint_service_permissions")` ->
  [DescribeVpcEndpointServicePermissionsPaginator](./paginators.md#describevpcendpointservicepermissionspaginator)
- `client.get_paginator("describe_vpc_endpoint_services")` ->
  [DescribeVpcEndpointServicesPaginator](./paginators.md#describevpcendpointservicespaginator)
- `client.get_paginator("describe_vpc_endpoints")` ->
  [DescribeVpcEndpointsPaginator](./paginators.md#describevpcendpointspaginator)
- `client.get_paginator("describe_vpc_peering_connections")` ->
  [DescribeVpcPeeringConnectionsPaginator](./paginators.md#describevpcpeeringconnectionspaginator)
- `client.get_paginator("describe_vpcs")` ->
  [DescribeVpcsPaginator](./paginators.md#describevpcspaginator)
- `client.get_paginator("get_associated_ipv6_pool_cidrs")` ->
  [GetAssociatedIpv6PoolCidrsPaginator](./paginators.md#getassociatedipv6poolcidrspaginator)
- `client.get_paginator("get_groups_for_capacity_reservation")` ->
  [GetGroupsForCapacityReservationPaginator](./paginators.md#getgroupsforcapacityreservationpaginator)
- `client.get_paginator("get_instance_types_from_instance_requirements")` ->
  [GetInstanceTypesFromInstanceRequirementsPaginator](./paginators.md#getinstancetypesfrominstancerequirementspaginator)
- `client.get_paginator("get_ipam_address_history")` ->
  [GetIpamAddressHistoryPaginator](./paginators.md#getipamaddresshistorypaginator)
- `client.get_paginator("get_ipam_pool_allocations")` ->
  [GetIpamPoolAllocationsPaginator](./paginators.md#getipampoolallocationspaginator)
- `client.get_paginator("get_ipam_pool_cidrs")` ->
  [GetIpamPoolCidrsPaginator](./paginators.md#getipampoolcidrspaginator)
- `client.get_paginator("get_ipam_resource_cidrs")` ->
  [GetIpamResourceCidrsPaginator](./paginators.md#getipamresourcecidrspaginator)
- `client.get_paginator("get_managed_prefix_list_associations")` ->
  [GetManagedPrefixListAssociationsPaginator](./paginators.md#getmanagedprefixlistassociationspaginator)
- `client.get_paginator("get_managed_prefix_list_entries")` ->
  [GetManagedPrefixListEntriesPaginator](./paginators.md#getmanagedprefixlistentriespaginator)
- `client.get_paginator("get_spot_placement_scores")` ->
  [GetSpotPlacementScoresPaginator](./paginators.md#getspotplacementscorespaginator)
- `client.get_paginator("get_transit_gateway_attachment_propagations")` ->
  [GetTransitGatewayAttachmentPropagationsPaginator](./paginators.md#gettransitgatewayattachmentpropagationspaginator)
- `client.get_paginator("get_transit_gateway_multicast_domain_associations")`
  ->
  [GetTransitGatewayMulticastDomainAssociationsPaginator](./paginators.md#gettransitgatewaymulticastdomainassociationspaginator)
- `client.get_paginator("get_transit_gateway_prefix_list_references")` ->
  [GetTransitGatewayPrefixListReferencesPaginator](./paginators.md#gettransitgatewayprefixlistreferencespaginator)
- `client.get_paginator("get_transit_gateway_route_table_associations")` ->
  [GetTransitGatewayRouteTableAssociationsPaginator](./paginators.md#gettransitgatewayroutetableassociationspaginator)
- `client.get_paginator("get_transit_gateway_route_table_propagations")` ->
  [GetTransitGatewayRouteTablePropagationsPaginator](./paginators.md#gettransitgatewayroutetablepropagationspaginator)
- `client.get_paginator("get_vpn_connection_device_types")` ->
  [GetVpnConnectionDeviceTypesPaginator](./paginators.md#getvpnconnectiondevicetypespaginator)
- `client.get_paginator("list_snapshots_in_recycle_bin")` ->
  [ListSnapshotsInRecycleBinPaginator](./paginators.md#listsnapshotsinrecyclebinpaginator)
- `client.get_paginator("search_local_gateway_routes")` ->
  [SearchLocalGatewayRoutesPaginator](./paginators.md#searchlocalgatewayroutespaginator)
- `client.get_paginator("search_transit_gateway_multicast_groups")` ->
  [SearchTransitGatewayMulticastGroupsPaginator](./paginators.md#searchtransitgatewaymulticastgroupspaginator)

<a id="get_waiter"></a>

### get_waiter

Type annotations for `aiobotocore.create_client("ec2").get_waiter` method with
overloads.

- `client.get_waiter("bundle_task_complete")` ->
  [BundleTaskCompleteWaiter](./waiters.md#bundletaskcompletewaiter)
- `client.get_waiter("conversion_task_cancelled")` ->
  [ConversionTaskCancelledWaiter](./waiters.md#conversiontaskcancelledwaiter)
- `client.get_waiter("conversion_task_completed")` ->
  [ConversionTaskCompletedWaiter](./waiters.md#conversiontaskcompletedwaiter)
- `client.get_waiter("conversion_task_deleted")` ->
  [ConversionTaskDeletedWaiter](./waiters.md#conversiontaskdeletedwaiter)
- `client.get_waiter("customer_gateway_available")` ->
  [CustomerGatewayAvailableWaiter](./waiters.md#customergatewayavailablewaiter)
- `client.get_waiter("export_task_cancelled")` ->
  [ExportTaskCancelledWaiter](./waiters.md#exporttaskcancelledwaiter)
- `client.get_waiter("export_task_completed")` ->
  [ExportTaskCompletedWaiter](./waiters.md#exporttaskcompletedwaiter)
- `client.get_waiter("image_available")` ->
  [ImageAvailableWaiter](./waiters.md#imageavailablewaiter)
- `client.get_waiter("image_exists")` ->
  [ImageExistsWaiter](./waiters.md#imageexistswaiter)
- `client.get_waiter("instance_exists")` ->
  [InstanceExistsWaiter](./waiters.md#instanceexistswaiter)
- `client.get_waiter("instance_running")` ->
  [InstanceRunningWaiter](./waiters.md#instancerunningwaiter)
- `client.get_waiter("instance_status_ok")` ->
  [InstanceStatusOkWaiter](./waiters.md#instancestatusokwaiter)
- `client.get_waiter("instance_stopped")` ->
  [InstanceStoppedWaiter](./waiters.md#instancestoppedwaiter)
- `client.get_waiter("instance_terminated")` ->
  [InstanceTerminatedWaiter](./waiters.md#instanceterminatedwaiter)
- `client.get_waiter("internet_gateway_exists")` ->
  [InternetGatewayExistsWaiter](./waiters.md#internetgatewayexistswaiter)
- `client.get_waiter("key_pair_exists")` ->
  [KeyPairExistsWaiter](./waiters.md#keypairexistswaiter)
- `client.get_waiter("nat_gateway_available")` ->
  [NatGatewayAvailableWaiter](./waiters.md#natgatewayavailablewaiter)
- `client.get_waiter("network_interface_available")` ->
  [NetworkInterfaceAvailableWaiter](./waiters.md#networkinterfaceavailablewaiter)
- `client.get_waiter("password_data_available")` ->
  [PasswordDataAvailableWaiter](./waiters.md#passworddataavailablewaiter)
- `client.get_waiter("security_group_exists")` ->
  [SecurityGroupExistsWaiter](./waiters.md#securitygroupexistswaiter)
- `client.get_waiter("snapshot_completed")` ->
  [SnapshotCompletedWaiter](./waiters.md#snapshotcompletedwaiter)
- `client.get_waiter("spot_instance_request_fulfilled")` ->
  [SpotInstanceRequestFulfilledWaiter](./waiters.md#spotinstancerequestfulfilledwaiter)
- `client.get_waiter("subnet_available")` ->
  [SubnetAvailableWaiter](./waiters.md#subnetavailablewaiter)
- `client.get_waiter("system_status_ok")` ->
  [SystemStatusOkWaiter](./waiters.md#systemstatusokwaiter)
- `client.get_waiter("volume_available")` ->
  [VolumeAvailableWaiter](./waiters.md#volumeavailablewaiter)
- `client.get_waiter("volume_deleted")` ->
  [VolumeDeletedWaiter](./waiters.md#volumedeletedwaiter)
- `client.get_waiter("volume_in_use")` ->
  [VolumeInUseWaiter](./waiters.md#volumeinusewaiter)
- `client.get_waiter("vpc_available")` ->
  [VpcAvailableWaiter](./waiters.md#vpcavailablewaiter)
- `client.get_waiter("vpc_exists")` ->
  [VpcExistsWaiter](./waiters.md#vpcexistswaiter)
- `client.get_waiter("vpc_peering_connection_deleted")` ->
  [VpcPeeringConnectionDeletedWaiter](./waiters.md#vpcpeeringconnectiondeletedwaiter)
- `client.get_waiter("vpc_peering_connection_exists")` ->
  [VpcPeeringConnectionExistsWaiter](./waiters.md#vpcpeeringconnectionexistswaiter)
- `client.get_waiter("vpn_connection_available")` ->
  [VpnConnectionAvailableWaiter](./waiters.md#vpnconnectionavailablewaiter)
- `client.get_waiter("vpn_connection_deleted")` ->
  [VpnConnectionDeletedWaiter](./waiters.md#vpnconnectiondeletedwaiter)
