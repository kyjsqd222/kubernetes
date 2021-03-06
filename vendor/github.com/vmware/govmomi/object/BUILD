package(default_visibility = ["//visibility:public"])

licenses(["notice"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_library",
)

go_library(
    name = "go_default_library",
    srcs = [
        "authorization_manager.go",
        "cluster_compute_resource.go",
        "common.go",
        "compute_resource.go",
        "custom_fields_manager.go",
        "customization_spec_manager.go",
        "datacenter.go",
        "datastore.go",
        "datastore_file.go",
        "datastore_path.go",
        "diagnostic_log.go",
        "diagnostic_manager.go",
        "distributed_virtual_portgroup.go",
        "distributed_virtual_switch.go",
        "extension_manager.go",
        "file_manager.go",
        "folder.go",
        "history_collector.go",
        "host_account_manager.go",
        "host_certificate_info.go",
        "host_certificate_manager.go",
        "host_config_manager.go",
        "host_datastore_browser.go",
        "host_datastore_system.go",
        "host_date_time_system.go",
        "host_firewall_system.go",
        "host_network_system.go",
        "host_service_system.go",
        "host_storage_system.go",
        "host_system.go",
        "host_virtual_nic_manager.go",
        "host_vsan_system.go",
        "http_nfc_lease.go",
        "list_view.go",
        "namespace_manager.go",
        "network.go",
        "network_reference.go",
        "option_manager.go",
        "ovf_manager.go",
        "resource_pool.go",
        "search_index.go",
        "storage_pod.go",
        "storage_resource_manager.go",
        "task.go",
        "types.go",
        "virtual_app.go",
        "virtual_device_list.go",
        "virtual_disk_manager.go",
        "virtual_machine.go",
        "vmware_distributed_virtual_switch.go",
    ],
    tags = ["automanaged"],
    deps = [
        "//vendor/github.com/vmware/govmomi/property:go_default_library",
        "//vendor/github.com/vmware/govmomi/session:go_default_library",
        "//vendor/github.com/vmware/govmomi/task:go_default_library",
        "//vendor/github.com/vmware/govmomi/vim25:go_default_library",
        "//vendor/github.com/vmware/govmomi/vim25/methods:go_default_library",
        "//vendor/github.com/vmware/govmomi/vim25/mo:go_default_library",
        "//vendor/github.com/vmware/govmomi/vim25/progress:go_default_library",
        "//vendor/github.com/vmware/govmomi/vim25/soap:go_default_library",
        "//vendor/github.com/vmware/govmomi/vim25/types:go_default_library",
    ],
)

filegroup(
    name = "package-srcs",
    srcs = glob(["**"]),
    tags = ["automanaged"],
    visibility = ["//visibility:private"],
)

filegroup(
    name = "all-srcs",
    srcs = [":package-srcs"],
    tags = ["automanaged"],
)
