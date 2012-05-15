## -*- Mode: python; py-indent-offset: 4; indent-tabs-mode:nil; coding: utf-8; -*-

def build(bld):
	module = bld.create_ns3_module('yanci', ['network', 'internet'])
	module.include = '.'
	module.source = [
		'model/yanci-header.cc',
		'model/yanci-hash.cc',
		'model/yanci-neighbor.cc',
		'model/yanci-queue.cc',
		'model/yanci-packet-info.cc',
		'model/yanci-protocol.cc',
		'model/yanci-packet-pool.cc',
		'model/yanci-device.cc',
		'helper/yanci-helper.cc',
	]

	headers = bld.new_task_gen(features=['ns3header'])
	headers.module = 'yanci'
	headers.source = [
		'model/yanci-header.h',
		'model/yanci-hash.h',
		'model/yanci-neighbor.h',
		'model/yanci-queue.h',
		'model/yanci-packet-info.h',
		'model/yanci-protocol.h',
		'model/yanci-packet-pool.h',
		'model/yanci-device.h',
		'helper/yanci-helper.h',
	]
