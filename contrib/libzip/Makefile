# Alternative GNU Make project makefile autogenerated by Premake

ifndef config
  config=release
endif

ifndef verbose
  SILENT = @
endif

.PHONY: clean prebuild

SHELLTYPE := posix
ifeq (.exe,$(findstring .exe,$(ComSpec)))
	SHELLTYPE := msdos
endif

# Configurations
# #############################################

RESCOMP = windres
INCLUDES += -Iinclude
FORCE_INCLUDE +=
ALL_CPPFLAGS += $(CPPFLAGS) -MD -MP $(DEFINES) $(INCLUDES)
ALL_RESFLAGS += $(RESFLAGS) $(DEFINES) $(INCLUDES)
LIBS +=
LDDEPS +=
LINKCMD = $(AR) -rcs "$@" $(OBJECTS)
define PREBUILDCMDS
endef
define PRELINKCMDS
endef
define POSTBUILDCMDS
endef

ifeq ($(config),release)
TARGETDIR = bin/Release
TARGET = $(TARGETDIR)/libzip-lib.a
OBJDIR = obj/Release
DEFINES += -DPREMAKE_COMPRESSION -DCURL_STATICLIB -DPREMAKE_CURL -DNDEBUG -DN_FSEEKO -DHAVE_SSIZE_T_LIBZIP -DHAVE_CONFIG_H
ALL_CFLAGS += $(CFLAGS) $(ALL_CPPFLAGS) -O3 -w
ALL_CXXFLAGS += $(CXXFLAGS) $(ALL_CPPFLAGS) -O3 -w -fno-stack-protector
ALL_LDFLAGS += $(LDFLAGS) -s

else ifeq ($(config),debug)
TARGETDIR = bin/Debug
TARGET = $(TARGETDIR)/libzip-lib.a
OBJDIR = obj/Debug
DEFINES += -DPREMAKE_COMPRESSION -DCURL_STATICLIB -DPREMAKE_CURL -D_DEBUG -DN_FSEEKO -DHAVE_SSIZE_T_LIBZIP -DHAVE_CONFIG_H
ALL_CFLAGS += $(CFLAGS) $(ALL_CPPFLAGS) -g -w
ALL_CXXFLAGS += $(CXXFLAGS) $(ALL_CPPFLAGS) -g -w
ALL_LDFLAGS += $(LDFLAGS)

endif

# Per File Configurations
# #############################################


# File sets
# #############################################

GENERATED :=
OBJECTS :=

GENERATED += $(OBJDIR)/mkstemp.o
GENERATED += $(OBJDIR)/zip_add.o
GENERATED += $(OBJDIR)/zip_add_dir.o
GENERATED += $(OBJDIR)/zip_add_entry.o
GENERATED += $(OBJDIR)/zip_close.o
GENERATED += $(OBJDIR)/zip_delete.o
GENERATED += $(OBJDIR)/zip_dir_add.o
GENERATED += $(OBJDIR)/zip_dirent.o
GENERATED += $(OBJDIR)/zip_discard.o
GENERATED += $(OBJDIR)/zip_entry.o
GENERATED += $(OBJDIR)/zip_err_str.o
GENERATED += $(OBJDIR)/zip_error.o
GENERATED += $(OBJDIR)/zip_error_clear.o
GENERATED += $(OBJDIR)/zip_error_get.o
GENERATED += $(OBJDIR)/zip_error_get_sys_type.o
GENERATED += $(OBJDIR)/zip_error_strerror.o
GENERATED += $(OBJDIR)/zip_error_to_str.o
GENERATED += $(OBJDIR)/zip_extra_field.o
GENERATED += $(OBJDIR)/zip_extra_field_api.o
GENERATED += $(OBJDIR)/zip_fclose.o
GENERATED += $(OBJDIR)/zip_fdopen.o
GENERATED += $(OBJDIR)/zip_file_add.o
GENERATED += $(OBJDIR)/zip_file_error_clear.o
GENERATED += $(OBJDIR)/zip_file_error_get.o
GENERATED += $(OBJDIR)/zip_file_get_comment.o
GENERATED += $(OBJDIR)/zip_file_get_external_attributes.o
GENERATED += $(OBJDIR)/zip_file_get_offset.o
GENERATED += $(OBJDIR)/zip_file_rename.o
GENERATED += $(OBJDIR)/zip_file_replace.o
GENERATED += $(OBJDIR)/zip_file_set_comment.o
GENERATED += $(OBJDIR)/zip_file_set_external_attributes.o
GENERATED += $(OBJDIR)/zip_file_strerror.o
GENERATED += $(OBJDIR)/zip_filerange_crc.o
GENERATED += $(OBJDIR)/zip_fopen.o
GENERATED += $(OBJDIR)/zip_fopen_encrypted.o
GENERATED += $(OBJDIR)/zip_fopen_index.o
GENERATED += $(OBJDIR)/zip_fopen_index_encrypted.o
GENERATED += $(OBJDIR)/zip_fread.o
GENERATED += $(OBJDIR)/zip_get_archive_comment.o
GENERATED += $(OBJDIR)/zip_get_archive_flag.o
GENERATED += $(OBJDIR)/zip_get_compression_implementation.o
GENERATED += $(OBJDIR)/zip_get_encryption_implementation.o
GENERATED += $(OBJDIR)/zip_get_file_comment.o
GENERATED += $(OBJDIR)/zip_get_name.o
GENERATED += $(OBJDIR)/zip_get_num_entries.o
GENERATED += $(OBJDIR)/zip_get_num_files.o
GENERATED += $(OBJDIR)/zip_memdup.o
GENERATED += $(OBJDIR)/zip_name_locate.o
GENERATED += $(OBJDIR)/zip_new.o
GENERATED += $(OBJDIR)/zip_open.o
GENERATED += $(OBJDIR)/zip_rename.o
GENERATED += $(OBJDIR)/zip_replace.o
GENERATED += $(OBJDIR)/zip_set_archive_comment.o
GENERATED += $(OBJDIR)/zip_set_archive_flag.o
GENERATED += $(OBJDIR)/zip_set_default_password.o
GENERATED += $(OBJDIR)/zip_set_file_comment.o
GENERATED += $(OBJDIR)/zip_set_file_compression.o
GENERATED += $(OBJDIR)/zip_set_name.o
GENERATED += $(OBJDIR)/zip_source_buffer.o
GENERATED += $(OBJDIR)/zip_source_close.o
GENERATED += $(OBJDIR)/zip_source_crc.o
GENERATED += $(OBJDIR)/zip_source_deflate.o
GENERATED += $(OBJDIR)/zip_source_error.o
GENERATED += $(OBJDIR)/zip_source_file.o
GENERATED += $(OBJDIR)/zip_source_filep.o
GENERATED += $(OBJDIR)/zip_source_free.o
GENERATED += $(OBJDIR)/zip_source_function.o
GENERATED += $(OBJDIR)/zip_source_layered.o
GENERATED += $(OBJDIR)/zip_source_open.o
GENERATED += $(OBJDIR)/zip_source_pkware.o
GENERATED += $(OBJDIR)/zip_source_pop.o
GENERATED += $(OBJDIR)/zip_source_read.o
GENERATED += $(OBJDIR)/zip_source_stat.o
GENERATED += $(OBJDIR)/zip_source_window.o
GENERATED += $(OBJDIR)/zip_source_zip.o
GENERATED += $(OBJDIR)/zip_source_zip_new.o
GENERATED += $(OBJDIR)/zip_stat.o
GENERATED += $(OBJDIR)/zip_stat_index.o
GENERATED += $(OBJDIR)/zip_stat_init.o
GENERATED += $(OBJDIR)/zip_strerror.o
GENERATED += $(OBJDIR)/zip_string.o
GENERATED += $(OBJDIR)/zip_unchange.o
GENERATED += $(OBJDIR)/zip_unchange_all.o
GENERATED += $(OBJDIR)/zip_unchange_archive.o
GENERATED += $(OBJDIR)/zip_unchange_data.o
GENERATED += $(OBJDIR)/zip_utf-8.o
OBJECTS += $(OBJDIR)/mkstemp.o
OBJECTS += $(OBJDIR)/zip_add.o
OBJECTS += $(OBJDIR)/zip_add_dir.o
OBJECTS += $(OBJDIR)/zip_add_entry.o
OBJECTS += $(OBJDIR)/zip_close.o
OBJECTS += $(OBJDIR)/zip_delete.o
OBJECTS += $(OBJDIR)/zip_dir_add.o
OBJECTS += $(OBJDIR)/zip_dirent.o
OBJECTS += $(OBJDIR)/zip_discard.o
OBJECTS += $(OBJDIR)/zip_entry.o
OBJECTS += $(OBJDIR)/zip_err_str.o
OBJECTS += $(OBJDIR)/zip_error.o
OBJECTS += $(OBJDIR)/zip_error_clear.o
OBJECTS += $(OBJDIR)/zip_error_get.o
OBJECTS += $(OBJDIR)/zip_error_get_sys_type.o
OBJECTS += $(OBJDIR)/zip_error_strerror.o
OBJECTS += $(OBJDIR)/zip_error_to_str.o
OBJECTS += $(OBJDIR)/zip_extra_field.o
OBJECTS += $(OBJDIR)/zip_extra_field_api.o
OBJECTS += $(OBJDIR)/zip_fclose.o
OBJECTS += $(OBJDIR)/zip_fdopen.o
OBJECTS += $(OBJDIR)/zip_file_add.o
OBJECTS += $(OBJDIR)/zip_file_error_clear.o
OBJECTS += $(OBJDIR)/zip_file_error_get.o
OBJECTS += $(OBJDIR)/zip_file_get_comment.o
OBJECTS += $(OBJDIR)/zip_file_get_external_attributes.o
OBJECTS += $(OBJDIR)/zip_file_get_offset.o
OBJECTS += $(OBJDIR)/zip_file_rename.o
OBJECTS += $(OBJDIR)/zip_file_replace.o
OBJECTS += $(OBJDIR)/zip_file_set_comment.o
OBJECTS += $(OBJDIR)/zip_file_set_external_attributes.o
OBJECTS += $(OBJDIR)/zip_file_strerror.o
OBJECTS += $(OBJDIR)/zip_filerange_crc.o
OBJECTS += $(OBJDIR)/zip_fopen.o
OBJECTS += $(OBJDIR)/zip_fopen_encrypted.o
OBJECTS += $(OBJDIR)/zip_fopen_index.o
OBJECTS += $(OBJDIR)/zip_fopen_index_encrypted.o
OBJECTS += $(OBJDIR)/zip_fread.o
OBJECTS += $(OBJDIR)/zip_get_archive_comment.o
OBJECTS += $(OBJDIR)/zip_get_archive_flag.o
OBJECTS += $(OBJDIR)/zip_get_compression_implementation.o
OBJECTS += $(OBJDIR)/zip_get_encryption_implementation.o
OBJECTS += $(OBJDIR)/zip_get_file_comment.o
OBJECTS += $(OBJDIR)/zip_get_name.o
OBJECTS += $(OBJDIR)/zip_get_num_entries.o
OBJECTS += $(OBJDIR)/zip_get_num_files.o
OBJECTS += $(OBJDIR)/zip_memdup.o
OBJECTS += $(OBJDIR)/zip_name_locate.o
OBJECTS += $(OBJDIR)/zip_new.o
OBJECTS += $(OBJDIR)/zip_open.o
OBJECTS += $(OBJDIR)/zip_rename.o
OBJECTS += $(OBJDIR)/zip_replace.o
OBJECTS += $(OBJDIR)/zip_set_archive_comment.o
OBJECTS += $(OBJDIR)/zip_set_archive_flag.o
OBJECTS += $(OBJDIR)/zip_set_default_password.o
OBJECTS += $(OBJDIR)/zip_set_file_comment.o
OBJECTS += $(OBJDIR)/zip_set_file_compression.o
OBJECTS += $(OBJDIR)/zip_set_name.o
OBJECTS += $(OBJDIR)/zip_source_buffer.o
OBJECTS += $(OBJDIR)/zip_source_close.o
OBJECTS += $(OBJDIR)/zip_source_crc.o
OBJECTS += $(OBJDIR)/zip_source_deflate.o
OBJECTS += $(OBJDIR)/zip_source_error.o
OBJECTS += $(OBJDIR)/zip_source_file.o
OBJECTS += $(OBJDIR)/zip_source_filep.o
OBJECTS += $(OBJDIR)/zip_source_free.o
OBJECTS += $(OBJDIR)/zip_source_function.o
OBJECTS += $(OBJDIR)/zip_source_layered.o
OBJECTS += $(OBJDIR)/zip_source_open.o
OBJECTS += $(OBJDIR)/zip_source_pkware.o
OBJECTS += $(OBJDIR)/zip_source_pop.o
OBJECTS += $(OBJDIR)/zip_source_read.o
OBJECTS += $(OBJDIR)/zip_source_stat.o
OBJECTS += $(OBJDIR)/zip_source_window.o
OBJECTS += $(OBJDIR)/zip_source_zip.o
OBJECTS += $(OBJDIR)/zip_source_zip_new.o
OBJECTS += $(OBJDIR)/zip_stat.o
OBJECTS += $(OBJDIR)/zip_stat_index.o
OBJECTS += $(OBJDIR)/zip_stat_init.o
OBJECTS += $(OBJDIR)/zip_strerror.o
OBJECTS += $(OBJDIR)/zip_string.o
OBJECTS += $(OBJDIR)/zip_unchange.o
OBJECTS += $(OBJDIR)/zip_unchange_all.o
OBJECTS += $(OBJDIR)/zip_unchange_archive.o
OBJECTS += $(OBJDIR)/zip_unchange_data.o
OBJECTS += $(OBJDIR)/zip_utf-8.o

# Rules
# #############################################

all: $(TARGET)
	@:

$(TARGET): $(GENERATED) $(OBJECTS) $(LDDEPS) | $(TARGETDIR)
	$(PRELINKCMDS)
	@echo Linking zip-lib
	$(SILENT) $(LINKCMD)
	$(POSTBUILDCMDS)

$(TARGETDIR):
	@echo Creating $(TARGETDIR)
ifeq (posix,$(SHELLTYPE))
	$(SILENT) mkdir -p $(TARGETDIR)
else
	$(SILENT) mkdir $(subst /,\\,$(TARGETDIR))
endif

$(OBJDIR):
	@echo Creating $(OBJDIR)
ifeq (posix,$(SHELLTYPE))
	$(SILENT) mkdir -p $(OBJDIR)
else
	$(SILENT) mkdir $(subst /,\\,$(OBJDIR))
endif

clean:
	@echo Cleaning zip-lib
ifeq (posix,$(SHELLTYPE))
	$(SILENT) rm -f  $(TARGET)
	$(SILENT) rm -rf $(GENERATED)
	$(SILENT) rm -rf $(OBJDIR)
else
	$(SILENT) if exist $(subst /,\\,$(TARGET)) del $(subst /,\\,$(TARGET))
	$(SILENT) if exist $(subst /,\\,$(GENERATED)) del /s /q $(subst /,\\,$(GENERATED))
	$(SILENT) if exist $(subst /,\\,$(OBJDIR)) rmdir /s /q $(subst /,\\,$(OBJDIR))
endif

prebuild: | $(OBJDIR)
	$(PREBUILDCMDS)

ifneq (,$(PCH))
$(OBJECTS): $(GCH) | $(PCH_PLACEHOLDER)
$(GCH): $(PCH) | prebuild
	@echo $(notdir $<)
	$(SILENT) $(CC) -x c-header $(ALL_CFLAGS) -o "$@" -MF "$(@:%.gch=%.d)" -c "$<"
$(PCH_PLACEHOLDER): $(GCH) | $(OBJDIR)
ifeq (posix,$(SHELLTYPE))
	$(SILENT) touch "$@"
else
	$(SILENT) echo $null >> "$@"
endif
else
$(OBJECTS): | prebuild
endif


# File Rules
# #############################################

$(OBJDIR)/mkstemp.o: mkstemp.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_add.o: zip_add.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_add_dir.o: zip_add_dir.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_add_entry.o: zip_add_entry.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_close.o: zip_close.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_delete.o: zip_delete.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_dir_add.o: zip_dir_add.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_dirent.o: zip_dirent.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_discard.o: zip_discard.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_entry.o: zip_entry.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_err_str.o: zip_err_str.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_error.o: zip_error.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_error_clear.o: zip_error_clear.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_error_get.o: zip_error_get.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_error_get_sys_type.o: zip_error_get_sys_type.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_error_strerror.o: zip_error_strerror.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_error_to_str.o: zip_error_to_str.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_extra_field.o: zip_extra_field.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_extra_field_api.o: zip_extra_field_api.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_fclose.o: zip_fclose.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_fdopen.o: zip_fdopen.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_file_add.o: zip_file_add.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_file_error_clear.o: zip_file_error_clear.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_file_error_get.o: zip_file_error_get.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_file_get_comment.o: zip_file_get_comment.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_file_get_external_attributes.o: zip_file_get_external_attributes.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_file_get_offset.o: zip_file_get_offset.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_file_rename.o: zip_file_rename.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_file_replace.o: zip_file_replace.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_file_set_comment.o: zip_file_set_comment.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_file_set_external_attributes.o: zip_file_set_external_attributes.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_file_strerror.o: zip_file_strerror.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_filerange_crc.o: zip_filerange_crc.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_fopen.o: zip_fopen.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_fopen_encrypted.o: zip_fopen_encrypted.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_fopen_index.o: zip_fopen_index.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_fopen_index_encrypted.o: zip_fopen_index_encrypted.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_fread.o: zip_fread.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_get_archive_comment.o: zip_get_archive_comment.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_get_archive_flag.o: zip_get_archive_flag.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_get_compression_implementation.o: zip_get_compression_implementation.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_get_encryption_implementation.o: zip_get_encryption_implementation.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_get_file_comment.o: zip_get_file_comment.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_get_name.o: zip_get_name.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_get_num_entries.o: zip_get_num_entries.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_get_num_files.o: zip_get_num_files.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_memdup.o: zip_memdup.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_name_locate.o: zip_name_locate.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_new.o: zip_new.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_open.o: zip_open.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_rename.o: zip_rename.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_replace.o: zip_replace.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_set_archive_comment.o: zip_set_archive_comment.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_set_archive_flag.o: zip_set_archive_flag.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_set_default_password.o: zip_set_default_password.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_set_file_comment.o: zip_set_file_comment.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_set_file_compression.o: zip_set_file_compression.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_set_name.o: zip_set_name.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_source_buffer.o: zip_source_buffer.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_source_close.o: zip_source_close.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_source_crc.o: zip_source_crc.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_source_deflate.o: zip_source_deflate.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_source_error.o: zip_source_error.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_source_file.o: zip_source_file.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_source_filep.o: zip_source_filep.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_source_free.o: zip_source_free.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_source_function.o: zip_source_function.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_source_layered.o: zip_source_layered.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_source_open.o: zip_source_open.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_source_pkware.o: zip_source_pkware.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_source_pop.o: zip_source_pop.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_source_read.o: zip_source_read.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_source_stat.o: zip_source_stat.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_source_window.o: zip_source_window.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_source_zip.o: zip_source_zip.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_source_zip_new.o: zip_source_zip_new.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_stat.o: zip_stat.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_stat_index.o: zip_stat_index.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_stat_init.o: zip_stat_init.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_strerror.o: zip_strerror.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_string.o: zip_string.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_unchange.o: zip_unchange.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_unchange_all.o: zip_unchange_all.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_unchange_archive.o: zip_unchange_archive.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_unchange_data.o: zip_unchange_data.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"
$(OBJDIR)/zip_utf-8.o: zip_utf-8.c
	@echo "$(notdir $<)"
	$(SILENT) $(CC) $(ALL_CFLAGS) $(FORCE_INCLUDE) -o "$@" -MF "$(@:%.o=%.d)" -c "$<"

-include $(OBJECTS:%.o=%.d)
ifneq (,$(PCH))
  -include $(PCH_PLACEHOLDER).d
endif